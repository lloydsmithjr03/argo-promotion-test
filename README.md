
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 9258eb6640abe15b1e5e4f2a43ef1316b4ef9b4c
kustomize build ./envs/int-us-central
```