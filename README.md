# k8s-vector-telemetry-pipeline

Run [Vector](https://vector.dev/) as a sidecar container (running as agent) and stream data down to a central Vector (running as service).

https://kubernetes.io/docs/concepts/cluster-administration/logging/#cluster-level-logging-architectures

### Aspirational

- Inject sidecar with a MutatingAdmissionWebhook.
- If back pressure is required introduce a durable queue before the service.