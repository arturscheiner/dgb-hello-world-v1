# Step Name -> JSON Generations Super
## Component Denominator -> json-generator-connector

## Component Description

JSON Generator (Mock) creates a JSON object. This component accepts any input.

Check this component official documentation: [json-generator-connector](https://docs.digibee.com/documentation/components/tools/json-generator "Digibee json-generator-connector documentation")

## Component Configuration Details
### Documentation

O parâmetro referente à documentação descritiva do componente não foi preenchido ou está indisponível para este componente.

### Parameters

* JSON
The json to generate. Double braces expressions are allowed.

```
{
  "request": {
    "code": 213,
    "value": 4513423.1322,
    "description": "   test request   ",
    "items": [
      {
        "id": "12345",
        "name": "item 11",
        "quantity": 2
      },
      {
        "id": "54321",
        "name": "item 2",
        "quantity": 5
      }
    ],
    "items2": [
      {
        "id2": "12345",
        "name2": "item 1",
        "quantity2": 2
      },
      {
        "id2": "54321",
        "name2": "item 2",
        "quantity2": 5
      }
    ]
  }
}
```

* FailOnError
If true will stop pipeline with an error, if false will let the pipeline continue but the output will show a property success with value false.

```
false
```

## RAW Object

```
{"name":"json-generator-connector","type":"connector","stepName":"JSON Generations Super","params":{"json":"{\n  \"request\": {\n    \"code\": 213,\n    \"value\": 4513423.1322,\n    \"description\": \"   test request   \",\n    \"items\": [\n      {\n        \"id\": \"12345\",\n        \"name\": \"item 11\",\n        \"quantity\": 2\n      },\n      {\n        \"id\": \"54321\",\n        \"name\": \"item 2\",\n        \"quantity\": 5\n      }\n    ],\n    \"items2\": [\n      {\n        \"id2\": \"12345\",\n        \"name2\": \"item 1\",\n        \"quantity2\": 2\n      },\n      {\n        \"id2\": \"54321\",\n        \"name2\": \"item 2\",\n        \"quantity2\": 5\n      }\n    ]\n  }\n}","failOnError":false},"id":"01965f1c-2ead-48a4-88a8-d98a635f116f"}
```