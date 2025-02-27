
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 1f4a2c2eb004c4b19f345425c79cc1f21a22d422
kustomize build ./envs/int-us-central
```