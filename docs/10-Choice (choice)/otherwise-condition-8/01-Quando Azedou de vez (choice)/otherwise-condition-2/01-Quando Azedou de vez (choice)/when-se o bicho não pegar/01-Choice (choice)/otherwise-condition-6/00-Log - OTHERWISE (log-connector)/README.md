# Step Name -> Log - OTHERWISE
## Component Denominator -> log-connector

## Component Description

Log allows the creation of log registers inside a pipeline. It helps in the generation of steps traceability when you want so.

Check this component official documentation: [log-connector](https://docs.digibee.com/documentation/components/tools/log "Digibee log-connector documentation")

## Component Configuration Details
### Documentation

O parâmetro referente à documentação descritiva do componente não foi preenchido ou está indisponível para este componente.

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