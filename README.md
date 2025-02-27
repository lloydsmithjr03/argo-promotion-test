
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 3dc44ecec531e3b4a8a425fa715812e2bbe07002
kustomize build ./envs/dev-us-central
```