## tanzu package repository add

Add a repository

```
tanzu package repository add REPOSITORY_NAME  [flags]
```

### Examples

```

    # Add a repository in specified namespace which does not exist 	
    tanzu package repository add repo --url projects-stg.registry.vmware.com/tkg/standard-repo:v1.0.0 --namespace test-ns --create-namespace
```

### Options

```
      --create-namespace   Create namespace if the target namespace does not exist, optional
  -h, --help               help for add
      --url string         OCI registry url for package repository bundle
```

### Options inherited from parent commands

```
      --kubeconfig string   The path to the kubeconfig file, optional
      --log-file string     Log file path
  -n, --namespace string    Namespace for repository command, optional (default "default")
      --verbose int32       Number for the log level verbosity(0-9)
```

### SEE ALSO

* [tanzu package repository](tanzu_package_repository.md)	 - Repository operations

###### Auto generated by spf13/cobra on 15-Jul-2021