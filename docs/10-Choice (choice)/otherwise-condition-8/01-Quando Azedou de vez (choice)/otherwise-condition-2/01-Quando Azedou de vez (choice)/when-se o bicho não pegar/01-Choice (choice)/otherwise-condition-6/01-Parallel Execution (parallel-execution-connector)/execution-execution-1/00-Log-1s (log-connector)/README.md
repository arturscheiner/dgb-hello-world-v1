# Step Name -> Log-1s
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