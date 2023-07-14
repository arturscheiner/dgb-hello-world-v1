# Step Name -> Log
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
{"type":"connector","name":"log-connector","stepName":"Log","params":{"logLevel":"ERROR","message":"Error processing message {{ message.$.myField }}"},"id":"ca26adad-e8d6-4241-8901-c398ed66da47"}
```