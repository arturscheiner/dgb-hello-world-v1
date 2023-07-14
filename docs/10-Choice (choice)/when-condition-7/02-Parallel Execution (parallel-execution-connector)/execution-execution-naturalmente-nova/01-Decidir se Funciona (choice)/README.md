# Step Name -> Decidir se Funciona
## Connector Denominator -> generic

## Description

Digibee components are a powerful way to simplify the process of building integration flows. By using pre-built connectors and logic components, you can quickly and easily create complex integrations that connect different applications and services.

Check Digibee's official documentation: [generic](https://docs.digibee.com/documentation "Digibee documentation")

## Component Configuration Details
### Parameters

* id
```
58a231fa-160a-429f-ab86-7121e7c54030
```

* otherwise
```
se funcionar
```

* stepName
```
Decidir se Funciona
```

* type
```
choice
```

* when
```
[{"target":"se nao funcionar","jsonPath":"$"},{"target":"se funcionar parcialmente","jsonPath":"$"}]
```


## RAW Object

```
{"type":"choice","stepName":"Decidir se Funciona","when":[{"target":"se nao funcionar","jsonPath":"$"},{"target":"se funcionar parcialmente","jsonPath":"$"}],"otherwise":"se funcionar","id":"58a231fa-160a-429f-ab86-7121e7c54030"}
```