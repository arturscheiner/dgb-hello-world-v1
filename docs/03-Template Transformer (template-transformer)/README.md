# Step Name -> Template Transformer
## Connector Denominator -> template-transformer

### Dependencies

## Description

Template Transformer generates XML, HTML, text and other data from a specified template. The component can receive data to dynamically fill the template from a JSON received in its input message.

Check this component official documentation: [template-transformer](https://docs.digibee.com/documentation/components/tools/template-transformer "Digibee template-transformer documentation")

## Component Configuration Details
### Parameters

* Model Path - A dotted notation representation of the fields that should be used as source model and then transformed by the template.

```
request
```

* Body - The template (string value) to be replaced during runtime with data from the model

```
{ "lista" : [
    { "name": "abc",
        "teco": "lslsl"
    },
    <#list items as item >
            {
                "idx": ${item?index},
                "name_len": ${item.name?length},
                "items_len": ${items?size},
                "name": "${item.name}",
                "quantity": "${item.quantity}"
            }<#if (item?has_next)>,</#if>
    </#list>
],
    "items_qtde": ${items?size},
    "items2_qtde": ${items2?size},
    <#list 0..(${items2?size} as i>
        "items2_${i}_name2": "${items2[${i}].name2}"
    </#list><#if i != ${items2?size}>,</#if>
}
```

* Preserve Original
When enabled, original fields will be preserved. Original fields are preserved on a new field prefixed by _ (underline)

```
true
```

## RAW Object

```
{"type":"template-transformer","stepName":"Template Transformer","modelPath":"request","template":"{ \"lista\" : [\n    { \"name\": \"abc\",\n        \"teco\": \"lslsl\"\n    },\n    <#list items as item >\n            {\n                \"idx\": ${item?index},\n                \"name_len\": ${item.name?length},\n                \"items_len\": ${items?size},\n                \"name\": \"${item.name}\",\n                \"quantity\": \"${item.quantity}\"\n            }<#if (item?has_next)>,</#if>\n    </#list>\n],\n    \"items_qtde\": ${items?size},\n    \"items2_qtde\": ${items2?size},\n    <#list 0..(${items2?size} as i>\n        \"items2_${i}_name2\": \"${items2[${i}].name2}\"\n    </#list><#if i != ${items2?size}>,</#if>\n}","preserveOriginal":true,"id":"88e12735-1c97-42f5-9165-26a72004d576"}
```