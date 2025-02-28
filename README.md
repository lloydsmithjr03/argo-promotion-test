
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 88dcb5ab5a8b70977d88237ad6850ce7b240f8c6
kustomize build ./envs/prod-us-central
```