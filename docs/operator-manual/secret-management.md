# Secret Management

Argo CD is un-opinionated about how secrets are managed. There's many ways to do it and there's no one-size-fits-all solution. Here's some ways people are doing GitOps secrets:

* [Bitnami Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets)
* [Godaddy Kubernetes External Secrets](https://github.com/godaddy/kubernetes-external-secrets)
* [Hasicorp Vault](https://www.vaultproject.io)
* [Helm Secrets](https://github.com/futuresimple/helm-secrets)
* [Kustomize secret generator plugins](https://github.com/kubernetes-sigs/kustomize/blob/fd7a353df6cece4629b8e8ad56b71e30636f38fc/examples/kvSourceGoPlugin.md#secret-values-from-anywhere)
* [aws-secret-operator](https://github.com/mumoshu/aws-secret-operator)

For discussion, see [#1364](https://github.com/argoproj/argo-cd/issues/1364)