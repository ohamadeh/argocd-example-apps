# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/ohamadeh/argocd-example-apps
# cd into the cloned directory
git checkout ee84a110f831fdee29d3e616717944d26905b0ac
helm template . --name-template staging-helm-guestbook --include-crds
```
