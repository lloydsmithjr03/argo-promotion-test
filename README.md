
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 67bb452b47a98be75fda1b0239ae6ff2458f8ab7
kustomize build ./envs/prod-us-central
```