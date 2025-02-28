
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout cfc0335bf71c0ac0c09695dd2c64567ce2aa2cda
kustomize build ./envs/prod-us-central
```