
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout f838bc64765f692092e3cb90f2719f0d78fbbbd6
kustomize build ./envs/dev-us-central
```