
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 49bb8a341476789ef28a8482b1d23d2c312e9159
kustomize build ./envs/dev-us-central
```