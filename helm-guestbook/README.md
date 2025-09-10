# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/ohamadeh/argocd-example-apps
# cd into the cloned directory
git checkout a90d82f911e0fe05134ffa1ef9e8e5ce83ba0290
helm template . --name-template staging-helm-guestbook --include-crds
```
