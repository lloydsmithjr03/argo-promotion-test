
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout 2ca9538d9de7ec634ec5ed2cba2bb07381be3167
kustomize build ./envs/prod-us-central
```