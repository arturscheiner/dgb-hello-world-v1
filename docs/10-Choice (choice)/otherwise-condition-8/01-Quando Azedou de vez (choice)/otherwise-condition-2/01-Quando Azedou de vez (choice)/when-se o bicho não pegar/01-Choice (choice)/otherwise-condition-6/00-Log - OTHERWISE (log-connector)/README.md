# Step Name -> Log - OTHERWISE
## Connector Denominator -> log-connector

## Description

Log allows the creation of log registers inside a pipeline. It helps in the generation of steps traceability when you want so.

Check this component official documentation: [log-connector](https://docs.digibee.com/documentation/components/tools/log "Digibee log-connector documentation")

## Component Configuration Details
### Parameters

* logLevel
```
INFO
```

* message
```
Error processing message {{ message.$.myField }}
```


## RAW Object

```
{"type":"connector","name":"log-connector","stepName":"Log - OTHERWISE","params":{"logLevel":"INFO","message":"Error processing message {{ message.$.myField }}"},"id":"242a22a5-dd5c-4756-b7b7-f2d376af121a"}
```