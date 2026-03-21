# PostgreSQL Helm Chart

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Scalified/helm-postgres/blob/master/LICENSE)
[![Release](https://img.shields.io/github/v/release/Scalified/helm-postgres?style=flat-square)](https://github.com/Scalified/helm-postgres/releases/latest)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/scalified-postgres)](https://artifacthub.io/packages/helm/scalified-postgres/postgres)

## Requirements

* [Helm 3+](https://helm.sh)

## Installation

```bash
helm repo add scalified-postgres https://scalified.github.io/helm-postgres/
helm upgrade --install postgres scalified-postgres/postgres --create-namespace --namespace postgres
```

---

**Made with ❤️ by [Scalified](http://www.scalified.com)**
