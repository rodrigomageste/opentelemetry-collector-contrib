[comment]: <> (Code generated by mdatagen. DO NOT EDIT.)

# k8s/statefulset

**Parent Component:** k8s_cluster

## Default Metrics

The following metrics are emitted by default. Each of them can be disabled by applying the following configuration:

```yaml
metrics:
  <metric_name>:
    enabled: false
```

### k8s.statefulset.current_pods

The number of pods created by the StatefulSet controller from the StatefulSet version

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| 1 | Gauge | Int |

### k8s.statefulset.desired_pods

Number of desired pods in the stateful set (the `spec.replicas` field)

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| 1 | Gauge | Int |

### k8s.statefulset.ready_pods

Number of pods created by the stateful set that have the `Ready` condition

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| 1 | Gauge | Int |

### k8s.statefulset.updated_pods

Number of pods created by the StatefulSet controller from the StatefulSet version

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| 1 | Gauge | Int |

## Resource Attributes

| Name | Description | Values | Enabled |
| ---- | ----------- | ------ | ------- |
| k8s.namespace.name | The name of the namespace that the pod is running in. | Any Str | true |
| k8s.statefulset.name | The k8s statefulset name. | Any Str | true |
| k8s.statefulset.uid | The k8s statefulset uid. | Any Str | true |
| opencensus.resourcetype | The OpenCensus resource type. | Any Str | true |