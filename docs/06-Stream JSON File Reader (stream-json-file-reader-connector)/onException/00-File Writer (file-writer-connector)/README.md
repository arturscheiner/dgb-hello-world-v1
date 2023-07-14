# Step Name -> File Writer
## Connector Denominator -> generic

## Description

Digibee components are a powerful way to simplify the process of building integration flows. By using pre-built connectors and logic components, you can quickly and easily create complex integrations that connect different applications and services.

Check Digibee's official documentation: [generic](https://docs.digibee.com/documentation "Digibee documentation")

## Component Configuration Details
### Parameters

* id
```
d347038e-7147-4076-887a-cfaf3e4cccf0
```

* name
```
file-writer-connector
```

* params
```
{"fileName":"data.csv","inputData":"{{ message.data }}","fileExistsPolicy":"append"}
```

* stepName
```
File Writer
```

* type
```
connector
```


## RAW Object

```
{"type":"connector","name":"file-writer-connector","stepName":"File Writer","params":{"fileName":"data.csv","inputData":"{{ message.data }}","fileExistsPolicy":"append"},"id":"d347038e-7147-4076-887a-cfaf3e4cccf0"}
```