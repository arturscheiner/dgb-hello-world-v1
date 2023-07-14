# Step Name -> Log - onException
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
{"type":"connector","name":"log-connector","stepName":"Log - onException","params":{"logLevel":"ERROR","message":"Error processing message {{ message.$.myField }}"},"id":"61896575-6d21-4e5e-9fd9-747ef4bbff2b"}
```