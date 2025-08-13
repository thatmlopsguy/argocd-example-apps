
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/thatmlopsguy/argocd-example-apps
# cd into the cloned directory
git checkout 0f5b7862a3e0936281d7ace654d0301766c5c6c6
helm template . --name-template development-helm-guestbook --include-crds
```