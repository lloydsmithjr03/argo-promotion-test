
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 478b7d7fcebc7ea93849e371c12322f9a81e08fd
kustomize build ./envs/int-us-central
```