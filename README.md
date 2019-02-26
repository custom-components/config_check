# sensor.youtube

[![BuyMeCoffee][buymecoffeebedge]][buymecoffee]
[![custom_updater](https://img.shields.io/badge/custom__updater-true-success.svg)](https://github.com/custom-components/custom_updater)

_Run the CLI config_check from a service call._

When you run the service `config_check.run` it will generate a persistent_notification with the result.

### Example results

**Configuration is OK**  
![exampleok][exampleimgok]

**Configuration have issues**  
![exampleerror][exampleimgerror]

## Installation

To get started put `/custom_components/config_check/__init__.py` here:  
`<config directory>/custom_components/config_check/__init__.py`

## Example configuration.yaml

```yaml
config_check:
```

## Service

```text
config_check.run
```

***

[exampleimgok]: example_ok.png
[exampleimgerror]: example_error.png
[buymecoffee]: https://www.buymeacoffee.com/ludeeus
[buymecoffeebedge]: https://camo.githubusercontent.com/cd005dca0ef55d7725912ec03a936d3a7c8de5b5/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6275792532306d6525323061253230636f666665652d646f6e6174652d79656c6c6f772e737667