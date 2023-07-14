# Step Name -> Log do Block do For-Each
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
{"type":"connector","name":"log-connector","stepName":"Log do Block do For-Each","params":{"logLevel":"INFO","message":"Error processing message {{ message.$.myField }}"},"id":"9131657b-f0cc-4bff-9eb2-d94eaf84583b"}
```