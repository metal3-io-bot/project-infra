# Cluster Setup

Prow is running on an OpenShift cluster running on servers provided to the metal3.io project by [packet.net](https://packet.net).

## SSL

SSL certificates for applications (\*.apps.ci.metal3.io) and the API (api.ci.metal3.io) are managed by [cert-manager](https://github.com/jetstack/cert-manager) and issued by [letsencrypt](https://letsencrypt.org/).

See [ssl/README.md](ssl/README.md) for details.
