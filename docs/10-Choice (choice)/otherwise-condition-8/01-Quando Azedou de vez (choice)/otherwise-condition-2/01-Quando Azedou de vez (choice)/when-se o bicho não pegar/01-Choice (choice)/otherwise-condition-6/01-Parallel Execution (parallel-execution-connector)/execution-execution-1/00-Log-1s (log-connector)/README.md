# Step Name -> Log-1s
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
{"type":"connector","name":"log-connector","stepName":"Log-1s","params":{"logLevel":"ERROR","message":"Error processing message {{ message.$.myField }}"},"id":"7741ff31-84a6-4da7-b09b-4af51ca6fb1a"}
```