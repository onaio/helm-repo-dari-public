# **Public** Dari Helm Repository

To add new charts to this repository hosted on git:

```bash
$ helm package ~/my-helm-charts/my-app-chart
$ helm repo index .
```

To use the repository:

```bash
$ helm repo add dari-public \
  'https://raw.githubusercontent.com/onaio/helm-repo-dari-public/main/'
```

