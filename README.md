
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout c76b54a7cd3c4bc3d9e5c24db6296a18bbdca330
kustomize build ./envs/prod-us-central
```