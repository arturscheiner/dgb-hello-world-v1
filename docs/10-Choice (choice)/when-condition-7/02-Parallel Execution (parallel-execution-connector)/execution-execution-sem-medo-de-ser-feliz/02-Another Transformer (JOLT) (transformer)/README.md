# Step Name -> Another Transformer (JOLT)
## Connector Denominator -> transformer

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
{"type":"transformer","stepName":"Another Transformer (JOLT)","transformSpec":[{"operation":"shift","spec":{"body":{"*":"body.&"},"*":"&"}}],"id":"ad605276-c539-4acb-8c46-b8e343e58545"}
```