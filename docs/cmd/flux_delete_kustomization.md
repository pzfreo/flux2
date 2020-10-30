## flux delete kustomization

Delete a Kustomization resource

### Synopsis

The delete kustomization command deletes the given Kustomization from the cluster.

```
flux delete kustomization [name] [flags]
```

### Examples

```
  # Delete a kustomization and the Kubernetes resources created by it
  flux delete kustomization podinfo

```

### Options

```
  -h, --help   help for kustomization
```

### Options inherited from parent commands

```
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
  -n, --namespace string    the namespace scope for this operation (default "flux-system")
  -s, --silent              delete resource without asking for confirmation
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [flux delete](flux_delete.md)	 - Delete sources and resources
