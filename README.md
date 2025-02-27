
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 23d1d46ad3d166c17ea5d36f4b580762df13c678
kustomize build ./envs/dev-us-central
```