# Helm Charts - Library for Kubernetes

[![GitHub stars](https://img.shields.io/github/stars/Ealenn/charts?style=for-the-badge)](https://github.com/Ealenn/Echo-Server/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Ealenn/charts?style=for-the-badge)](https://github.com/Ealenn/Echo-Server/issues)
[![GitHub license](https://img.shields.io/github/license/Ealenn/charts?style=for-the-badge)](https://github.com/Ealenn/Echo-Server)

Popular applications, provided by [Ealen](https://github.com/Ealenn), charts are available in [Helm Hub](https://hub.helm.sh)

## TL;DR

```bash
helm repo add ealenn https://ealenn.github.io/charts
helm search ealenn
helm install ealenn/<chart>
```

## Projects

- [Echo-Server](https://hub.helm.sh/charts/ealenn/echo-server) REST Server Tests (Echo-Server) API
- [Picolors](https://hub.helm.sh/charts/ealenn/picolors) Get prominent color from an image

## Tools

```bash
docker run --rm --volume "$(pwd):/helm-docs" -u $(id -u) jnorwood/helm-docs:latest
```

- [norwoodj/helm-docs](https://github.com/norwoodj/helm-docs) A tool for automatically generating markdown documentation for helm charts
- [azure/setup-helm](https://github.com/Azure/setup-helm) Github Action for setting up helm
- [j12934/helm-gh-pages-action](https://github.com/J12934/helm-gh-pages-action) GitHub Action to package and deploy your Helm charts to GitHub Pages
