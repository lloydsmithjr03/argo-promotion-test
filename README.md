
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 2e0315eac911f4916083367da222b5949bdc7b56
kustomize build ./envs/int-us-central
```