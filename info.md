_Run the CLI config_check from a service call._

When you run the service `config_check.run` it will generate a persistent_notification with the result.

### Example results

**Configuration is OK**

![exampleok](https://github.com/custom-components/config_check/raw/master/example_ok.png)

**Configuration have issues**

![exampleerror](https://github.com/custom-components/config_check/raw/master/example_error.png)


## Example configuration.yaml

```yaml
config_check:
```

## Service

```text
config_check.run
```

You can add service data to the service call to make it run a service if it completes successfully.

**examples:**

```json
{
  "service": "script.chek_ok"
}
```

```json
{
  "service": "switch.turn_on",
  "service_data": {
    "entity_id": "switch.my_switch"
  }
}
```