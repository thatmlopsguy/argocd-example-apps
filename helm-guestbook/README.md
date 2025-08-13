
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/thatmlopsguy/argocd-example-apps
# cd into the cloned directory
git checkout 83b17793709d0f50a6e51c27fd0bb658c2ee05c3
helm template . --name-template staging-helm-guestbook --include-crds
```