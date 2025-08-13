
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/thatmlopsguy/argocd-example-apps
# cd into the cloned directory
git checkout 84c01e4d314c6257450ab354c6c10ef65adbe865
helm template . --name-template prod-helm-guestbook --include-crds
```