# audit_recipes
Lighthouse custom audit recipe suggestions. Current efforts are focused on using Lighthouse for accessibility assessments.

These recipes are guaranteed to work with [OpenAssessIt](https://github.com/OpenAssessItToolkit/openassessit) and the [OpenAssessIt Templates](https://github.com/OpenAssessItToolkit/openassessit_templates)

__Suggested use for desktop accessibility testing:__

```
lighthouse https://cats.com \
--config-path=/path/to/a11y-config-custom.js \
--output=json \
--output-path=/path/to/cats-audit.json \
--disable-device-emulation \
--chrome-flags='--headless --window-size=1300,600'
```

