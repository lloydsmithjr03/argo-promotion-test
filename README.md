
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout ccc362600ee40076f16fbc8312961a232b6ebd96
kustomize build ./envs/prod-us-central
```