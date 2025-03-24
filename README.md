# ESPHome Custom Component

With the release of ESPHome 2025.2.0, custom components were removed from the ESPHome core.

This component brings back support for such components.

## DISCLAIMER

Custom component code from ESPHome 2024.10.0 as-is.

## USAGE

Add the following to your project's YAML:
```
external_components:
  - source:
      type: git
      url: https://github.com/robertklep/esphome-custom-component
    components: [ custom, custom_component ]
```

## LICENSE

The ESPHome license (mixed GPL3/MIT) applies. See [the LICENSE file](LICENSE) for more information.
