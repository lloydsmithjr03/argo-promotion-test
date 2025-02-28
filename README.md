
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 55372c02a8e1d4469f29a873d74d5a60c3969f47
kustomize build ./envs/prod-us-central
```