
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout e95e76d4629a4676be52c7ca7780ce58ab99d067
kustomize build ./envs/dev-us-central
```