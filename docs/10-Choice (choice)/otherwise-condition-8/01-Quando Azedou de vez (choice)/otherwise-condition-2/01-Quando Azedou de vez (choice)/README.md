# Step Name -> Quando Azedou de vez
## Connector Denominator -> generic

## Description

Digibee components are a powerful way to simplify the process of building integration flows. By using pre-built connectors and logic components, you can quickly and easily create complex integrations that connect different applications and services.

Check Digibee's official documentation: [generic](https://docs.digibee.com/documentation "Digibee documentation")

## Component Configuration Details
### Parameters

* id
```
fd9b78c2-74bb-4cd9-87ec-3814b9e0a6b7
```

* otherwise
```
se o bicho pegar
```

* stepName
```
Quando Azedou de vez
```

* type
```
choice
```

* when
```
[{"target":"se o bicho não pegar","jsonPath":"$"}]
```


## RAW Object

```
{"type":"choice","stepName":"Quando Azedou de vez","when":[{"target":"se o bicho não pegar","jsonPath":"$"}],"otherwise":"se o bicho pegar","id":"fd9b78c2-74bb-4cd9-87ec-3814b9e0a6b7"}
```