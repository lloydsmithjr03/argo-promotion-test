
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 8e8bfeeedbedbd6099f71d619ad9797ac5f4f40a
kustomize build ./envs/prod-us-central
```