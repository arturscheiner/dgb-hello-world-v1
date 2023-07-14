# Step Name -> Stream DB V3
## Connector Denominator -> generic

## Description

Digibee components are a powerful way to simplify the process of building integration flows. By using pre-built connectors and logic components, you can quickly and easily create complex integrations that connect different applications and services.

Check Digibee's official documentation: [generic](https://docs.digibee.com/documentation "Digibee documentation")

## Component Configuration Details
### Parameters

* accountLabel
```
mysql-2
```

* id
```
23961bee-5dbc-4435-98a3-223892db04df
```

* name
```
stream-db-connector-v3
```

* params
```
{"url":"jdbc:mysql://35.223.175.97/db-training","sql":"select * from clientes LIMIT 2","itemIdentifier":"codigo","parallel":false,"failOnError":false,"keepConnection":true,"onProcess":"23961bee-5dbc-4435-98a3-223892db04df-onProcessTrack"}
```

* stepName
```
Stream DB V3
```

* type
```
connector
```


## RAW Object

```
{"type":"connector","name":"stream-db-connector-v3","accountLabel":"mysql-2","stepName":"Stream DB V3","params":{"url":"jdbc:mysql://35.223.175.97/db-training","sql":"select * from clientes LIMIT 2","itemIdentifier":"codigo","parallel":false,"failOnError":false,"keepConnection":true,"onProcess":"23961bee-5dbc-4435-98a3-223892db04df-onProcessTrack"},"id":"23961bee-5dbc-4435-98a3-223892db04df"}
```