
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 4cc05199a906dcb2c49fa5cd1c34788047260d05
kustomize build ./envs/prod-us-central
```