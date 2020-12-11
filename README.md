# Tekton sample pipeline using buildah

This is Tekton sample pipeline using the [upstream buildah task](https://github.com/tektoncd/catalog/tree/master/task/buildah/0.1) to build a sample application.

## Get started

```bash
oc new-project bud
oc apply -f tasks.yaml
oc apply -f pipeline.yaml
oc create -f pipelinerun.yaml
```
