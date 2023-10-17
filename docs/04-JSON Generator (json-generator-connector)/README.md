# Step Name -> JSON Generator
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
    "requestx": {{ TOJSON(message.request) }}
}
```

* FailOnError
If true will stop pipeline with an error, if false will let the pipeline continue but the output will show a property success with value false.

```
false
```

## RAW Object

```
{"name":"json-generator-connector","type":"connector","stepName":"JSON Generator","params":{"json":"{\n    \"requestx\": {{ TOJSON(message.request) }}\n}","failOnError":false},"id":"78007a5b-c4af-43ba-bb40-18d9c9739a64"}
```