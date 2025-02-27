
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout e618e1c96a705217f4776ecdec171a7747af73d9
kustomize build ./envs/dev-us-central
```