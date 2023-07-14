# Step Name -> Transformer (JOLTA)
## Connector Denominator -> transformer

### Dependencies

## Description

Transformer (JOLT) allows the manipulation of a JSON through JOLT technology.

Check this component official documentation: [transformer](https://docs.digibee.com/documentation/components/tools/transformer-jolt "Digibee transformer documentation")

## Component Configuration Details
### Parameters

* Type Properties
Area to include the JOLT transformations.

```
[
  {
    "operation": "shift",
    "spec": {
      "body": {
        "*": "body.&"
      },
      "*": "&"
    }
  }
]
```

## RAW Object

```
{"type":"transformer","stepName":"Transformer (JOLTA)","transformSpec":[{"operation":"shift","spec":{"body":{"*":"body.&"},"*":"&"}}],"id":"58fe81e8-cc2d-4907-9d69-42d8f844b2ee"}
```