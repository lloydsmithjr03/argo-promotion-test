
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 70a523ebb08ee2c24fd913dca464cd82baa8e707
kustomize build ./envs/prod-us-central
```