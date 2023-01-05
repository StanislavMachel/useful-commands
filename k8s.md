# K8s cheatsheet

Displays merged kubeconfig settings or a specified kubeconfig file

```shell
kubectl config view
```

```shell
kubectl config use-context <context>
```

See external secrets

```shell
kubectl get externalsecrets.kubernetes-client.io
```


```shell
kubectl describe externalsecrets.kubernetes-client.io <credential_value>
```

```shell
kubectl config rename-context <context name> <new context name>
```

Check current context
```shell
kubectl config current-context
```
Execute shell in pod

```sh
kubectl exec --stdin --tty <pod_name> -- sh
```

Get avaliable contexts

```sh
kubectl config get-contexts
```

Rename context

```sh
kubectl config rename-context old-name new-name
```

```sh
kubectl config use-context <context_name>
```


<!-- kubectl config unset users.gke_project_zone_name

kubectl config unset contexts.aws_cluster1-kubernetes

kubectl config unset clusters.foobar-baz -->