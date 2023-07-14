# Step Name -> Logs
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
{"type":"connector","name":"log-connector","stepName":"Logs","params":{"logLevel":"ERROR","message":"Error processing message {{ message.$.myField }}"},"id":"bdbcac2a-0f5a-426b-b6c3-a12020dcaa60"}
```