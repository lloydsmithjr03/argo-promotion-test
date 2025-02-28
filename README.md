
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout d2e3bd253e4ded39f417e01b0ebfcd0793e9b1bd
kustomize build ./envs/prod-us-central
```