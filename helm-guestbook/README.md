
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/thatmlopsguy/argocd-example-apps
# cd into the cloned directory
git checkout f006102d8d78c21d3fa929201fbdd19d44becbbc
helm template . --name-template staging-helm-guestbook --include-crds
```