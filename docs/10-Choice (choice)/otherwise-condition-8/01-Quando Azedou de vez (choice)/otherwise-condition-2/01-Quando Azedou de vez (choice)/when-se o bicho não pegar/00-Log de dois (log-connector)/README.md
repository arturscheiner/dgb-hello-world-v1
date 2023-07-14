# Step Name -> Log de dois
## Connector Denominator -> log-connector

## Description

Log allows the creation of log registers inside a pipeline. It helps in the generation of steps traceability when you want so.

Check this component official documentation: [log-connector](https://docs.digibee.com/documentation/components/tools/log "Digibee log-connector documentation")

## Component Configuration Details
### Parameters

* logLevel
```
ERROR
```

* message
```
Error processing message {{ message.$.myField }}
```


## RAW Object

```
{"type":"connector","name":"log-connector","stepName":"Log de dois","params":{"logLevel":"ERROR","message":"Error processing message {{ message.$.myField }}"},"id":"05fd9ada-c009-4d76-8fa2-2101ae51eb2c"}
```