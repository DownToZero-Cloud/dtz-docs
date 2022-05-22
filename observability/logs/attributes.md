# Attributes

Any client can define an arbitrary set of attributes for its logs.

Some attributes are commonly defined throughout various sources.

## GCP

* gcp.resource.type

## Kubernetes

* k8s.namespace.name
* k8s.pod.name
* k8s.container.name
* k8s.pod.uid

## Http

* http.uri
* http.user\_agent
* http.verb
* http.status
* http.version

## Stripe

* stripe.event.type
* stripe.event.id
* stripe.charge.amount
* stripe.charge.amount\_refunded
* stripe.charge.captured
* stripe.charge.currency
* stripe.charge.description
* stripe.charge.disputed
* stripe.charge.failure\_code
* stripe.charge.failure\_message
* stripe.charge.paid
* stripe.charge.refunded
* stripe.payment\_intent.id
* stripe.payment\_intent.amount
* stripe.payment\_intent.currency
* stripe.payment\_intent.status

