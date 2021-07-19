***Cloud Native Runtimes for Tanzu*** is a set of capabilities that enables developers to leverage the power of Kubernetes for serverless use cases without first having to master the Kubernetes API. Based on the open source Knative project, Cloud Native Runtimes for Tanzu can be used by itself or in concert with other Tanzu capabilities to quickly get modern cloud native applications with event-based architectures up and running on Kubernetes, regardless of a developer’s level of experience with the platform.

Cloud Native Runtimes gives developers and application operators (who are sometimes the same person!) a simplified way to manipulate Kubernetes to accomplish serverless use cases through Knative. This enables developers to:

- Be more productive on Kubernetes, faster – Deploy, scale, access, and manage containerized workloads without writing Kubernetes manifests or other templates using Knative Serving. 

- Build event-based applications that span multiple workload types – Access a Knative eventing resource that can trigger Kubernetes workloads based on external events using Knative Eventing.


```terminal:execute
command: echo "Execute command."
```


```terminal:execute
command: echo "Execute command - t1"
session: 1
```

```terminal:execute
command: echo "Execute command - t2"
session: 2
```

```terminal:execute-all
command: echo "Execute command in all"
```


```workshop:copy
text: echo "Text to copy."
```

```workshop:copy-and-edit
text: echo "Text to copy and edit."
```

```dashboard:open-url
url: https://www.vmware.com/
```

```dashboard:create-dashboard
name: created-vmware-dash
url: https://www.vmware.com/
```

```dashboard:create-dashboard
name: Example
url: terminal:example
```

```dashboard:reload-dashboard
name: created-vmware-dash
```

```dashboard:delete-dashboard
name: created-vmware-dash
```

```editor:open-file
file: /opt/workshop/setup/eventing-broker.yaml
```

```editor:select-matching-text
file: /opt/workshop/setup/eventing-broker.yaml
text: "metadata: "
```

