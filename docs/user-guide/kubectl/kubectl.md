---
---
<!-- BEGIN MUNGE: UNVERSIONED_WARNING -->


<!-- END MUNGE: UNVERSIONED_WARNING -->

## kubectl

kubectl controls the Kubernetes cluster manager

### Synopsis


kubectl controls the Kubernetes cluster manager.

Find more information at https://github.com/kubernetes/kubernetes.

```
kubectl
```

### Options

```
      --alsologtostderr[=false]: log to standard error as well as files
      --api-version="": The API version to use when talking to the server
      --certificate-authority="": Path to a cert. file for the certificate authority.
      --client-certificate="": Path to a client certificate file for TLS.
      --client-key="": Path to a client key file for TLS.
      --cluster="": The name of the kubeconfig cluster to use
      --context="": The name of the kubeconfig context to use
      --insecure-skip-tls-verify[=false]: If true, the server's certificate will not be checked for validity. This will make your HTTPS connections insecure.
      --kubeconfig="": Path to the kubeconfig file to use for CLI requests.
      --log-backtrace-at=:0: when logging hits line file:N, emit a stack trace
      --log-dir="": If non-empty, write log files in this directory
      --log-flush-frequency=5s: Maximum number of seconds between log flushes
      --logtostderr[=true]: log to standard error instead of files
      --match-server-version[=false]: Require server version to match client version
      --namespace="": If present, the namespace scope for this CLI request.
      --password="": Password for basic authentication to the API server.
  -s, --server="": The address and port of the Kubernetes API server
      --stderrthreshold=2: logs at or above this threshold go to stderr
      --token="": Bearer token for authentication to the API server.
      --user="": The name of the kubeconfig user to use
      --username="": Username for basic authentication to the API server.
      --v=0: log level for V logs
      --vmodule=: comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [kubectl annotate](../kubectl_annotate)	 - Update the annotations on a resource
* [kubectl api-versions](../kubectl_api-versions)	 - Print the supported API versions on the server, in the form of "group/version".
* [kubectl apply](../kubectl_apply)	 - Apply a configuration to a resource by filename or stdin
* [kubectl attach](../kubectl_attach)	 - Attach to a running container.
* [kubectl autoscale](../kubectl_autoscale)	 - Auto-scale a deployment or replication controller
* [kubectl cluster-info](../kubectl_cluster-info)	 - Display cluster info
* [kubectl config](../kubectl_config)	 - config modifies kubeconfig files
* [kubectl convert](../kubectl_convert)	 - Convert config files between different API versions
* [kubectl cordon](../kubectl_cordon)	 - Mark node as unschedulable
* [kubectl create](../kubectl_create)	 - Create a resource by filename or stdin
* [kubectl delete](../kubectl_delete)	 - Delete resources by filenames, stdin, resources and names, or by resources and label selector.
* [kubectl describe](../kubectl_describe)	 - Show details of a specific resource or group of resources
* [kubectl drain](../kubectl_drain)	 - Drain node in preparation for maintenance
* [kubectl edit](../kubectl_edit)	 - Edit a resource on the server
* [kubectl exec](../kubectl_exec)	 - Execute a command in a container.
* [kubectl explain](../kubectl_explain)	 - Documentation of resources.
* [kubectl expose](../kubectl_expose)	 - Take a replication controller, service or pod and expose it as a new Kubernetes Service
* [kubectl get](../kubectl_get)	 - Display one or many resources
* [kubectl label](../kubectl_label)	 - Update the labels on a resource
* [kubectl logs](../kubectl_logs)	 - Print the logs for a container in a pod.
* [kubectl namespace](../kubectl_namespace)	 - SUPERSEDED: Set and view the current Kubernetes namespace
* [kubectl patch](../kubectl_patch)	 - Update field(s) of a resource using strategic merge patch.
* [kubectl port-forward](../kubectl_port-forward)	 - Forward one or more local ports to a pod.
* [kubectl proxy](../kubectl_proxy)	 - Run a proxy to the Kubernetes API server
* [kubectl replace](../kubectl_replace)	 - Replace a resource by filename or stdin.
* [kubectl rolling-update](../kubectl_rolling-update)	 - Perform a rolling update of the given ReplicationController.
* [kubectl rollout](../kubectl_rollout)	 - rollout manages a deployment
* [kubectl run](../kubectl_run)	 - Run a particular image on the cluster.
* [kubectl scale](../kubectl_scale)	 - Set a new size for a Replication Controller, Job, or Deployment.
* [kubectl uncordon](../kubectl_uncordon)	 - Mark node as schedulable
* [kubectl version](../kubectl_version)	 - Print the client and server version information.

###### Auto generated by spf13/cobra on 19-Jan-2016