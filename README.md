
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 0e2308d555fa204a99999cc3d087beac1ddc2bb3
kustomize build ./envs/dev-us-central
```