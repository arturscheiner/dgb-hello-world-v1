# Step Name -> Event Publisher
## Connector Denominator -> event-publisher-connector

## Description

Event Publisher publishes an event for other configured pipelines to listen to it and have a chance to react when the publishing happens.

Check this component official documentation: [event-publisher-connector](https://docs.digibee.com/documentation/components/queues-and-messaging/event-publisher "Digibee event-publisher-connector documentation")

## Component Configuration Details
### Parameters

* body
```
{{ message.$ }}
```

* eventName
```
{{ DEFAULT(message.eventName, "new-event") }}
```

* showSendEventLog
```
false
```

* stopOnError
```
false
```


## RAW Object

```
{"type":"connector","stepName":"Event Publisher","name":"event-publisher-connector","params":{"eventName":"{{ DEFAULT(message.eventName, \"new-event\") }}","body":"{{ message.$ }}","showSendEventLog":false,"stopOnError":false},"id":"b582f763-39f9-4ae7-82e8-110c50af6f08"}
```