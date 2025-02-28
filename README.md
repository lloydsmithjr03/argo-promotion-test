
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 88aa4eee5beb4bc0a568872abeef220aff0be1a7
kustomize build ./envs/prod-us-central
```