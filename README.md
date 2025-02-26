
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 546306193ca0ed921da19bc97f47a200b144b1ed
kustomize build ./envs/dev-us-central
```