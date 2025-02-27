
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argo-promotion-test.git
# cd into the cloned directory
git checkout f84eea278d96a5688c9c5d36ca49a70893042b8c
kustomize build ./envs/dev-us-central
```