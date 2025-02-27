
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 943a9d3727c5e950b0e4957354cab6884da9cede
kustomize build ./envs/dev-us-central
```