# Step Name -> Log de Validação Inicial
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
{"type":"connector","name":"log-connector","stepName":"Log de Validação Inicial","params":{"logLevel":"INFO","message":"Error processing message {{ message.$.myField }}"},"id":"6b17c8d5-1234-4472-a99d-4c77a04141eb"}
```