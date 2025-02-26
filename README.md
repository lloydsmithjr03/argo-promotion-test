
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout e0dfc5d464ac57084f6f496b76488e2f28808ead
kustomize build ./envs/int-us-central
```