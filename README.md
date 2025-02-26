
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 79da6e0b00575af6d147defcde05db01266627e0
kustomize build ./envs/prod-us-central
```