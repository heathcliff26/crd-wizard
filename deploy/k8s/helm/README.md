# CR(D) Wizard Helm Chart

This Helm chart deploys CR(D) Wizard.

For more details see [CR(D) Wizard](https://github.com/pehlicd/crd-wizard).

## Prerequisites

- Kubernetes 1.33+
- Helm 4.2+
- FluxCD installed in the cluster (recommended)

## Installation

### Installing from OCI Registry (GitHub Packages)

```bash
# Install the chart
helm install crd-wizard oci://ghcr.io/pehlicd/helm-charts/crd-wizard --version <version>
```
