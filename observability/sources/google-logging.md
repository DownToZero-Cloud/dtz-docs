# Google Logging

Google supports log forwarding through Log Routers. You can configure a router to forward all logs into a Pub/Sub Topic. A push subcription then forward the log entry to DTZ.

To configure the Push endpoint you can use the following endpoint.

```
https://observability.dtz.rocks/gcp/logs?apiKey=00000000-0000-0000-0000-000000000000&contextId=00000000-0000-0000-0000-000000b25aa6
```

### Log interpretation

* text payload is shown as payload
* json payload is transformed into attributes one-by-one
* tags are transformed into attributes one-by-one
