# rapidast-tekton

## Create a Tekton bundle

task
```
$ tkn bundle push quay.io/jechoi/bundle:rapidast -f rapidast-task-for-tkn-bundle.yaml
```

pipeline
```
$ tkn bundle push quay.io/jechoi/bundle:rapidast-pipeline -f rapidast-pipeline.yaml
```
