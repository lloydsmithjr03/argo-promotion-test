
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 4669ec62eda8658e6ea8854ca9e27ae3fc407955
kustomize build ./envs/prod-us-central
```