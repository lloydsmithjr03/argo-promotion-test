
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 1c4112e6b42436eec24d06fcd4e74792e960bbe4
kustomize build ./envs/dev-us-central
```