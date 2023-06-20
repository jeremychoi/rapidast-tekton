# rapidast-tekton

Examples of DAST scanning (via [RapiDAST](https://github.com/RedHatProductSecurity/rapidast)) using Tekton pipeline and task. 
This can also help Red Hat Trusted Application Pipeline (RHTAP) provide DAST scanning to its users' applications.

## Run RapiDAST task with git resolver

See `rapidast-pipeline-git-resolver.yaml`

## Run RapiDAST task with a Tekton bundle

A Tekton bundle with RapiDAST task can be created as follow:

```
$ tkn bundle push quay.io/jechoi/bundle:rapidast -f rapidast-task.yaml
```

See `rapidast-pipeline-for-bundle.yaml` to refer to the task.
