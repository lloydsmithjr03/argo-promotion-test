
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout e26f5e48d524cf1cc344ca66f7a764a3022fb0cd
kustomize build ./envs/dev-us-central
```