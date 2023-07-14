# Step Name -> Log-2s
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
{"type":"connector","name":"log-connector","stepName":"Log-2s","params":{"logLevel":"ERROR","message":"Error processing message {{ message.$.myField }}"},"id":"99bf0ce8-0571-4ac9-a071-a322ece58c48"}
```