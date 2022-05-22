# Stripe

Stripe supports the forwarding of events through Webhooks. You can configure a webhook endpoint to receive all available events.

The endpoint would look like the following sample.

```
https://observability.dtz.rocks/stripe/webhook?apiKey=00000000-0000-0000-0000-000000000000&contextId=00000000-0000-0000-0000-000000b25aa6
```

### Log interpretation

* all structured data from the event is translated into attributes

### Implemented Events

* Charge
* Payment intent
