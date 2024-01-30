# Admiral Helm Charts

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Chart Publish](https://github.com/DataliftHQ/admiral-helm/actions/workflows/publish.yaml/badge.svg?branch=master)](https://github.com/DataliftHQ/datalift-helm/actions/workflows/publish.yaml)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/admiral)](https://artifacthub.io/packages/search?repo=admiral)

Admiral Helm is a collection charts for [https://admiral.io](https://admiral.io) projects. The charts can be added using following command:

```bash
helm repo add admiral https://charts.admiral.io
```

The charts published currently by this repository are the following:

| Chart name | Status | Remark |
|------------|--------|--------|
| [admiral-agent](https://github.com/DataliftHQ/admiral-helm/tree/master/charts/admiral-agent)   | Alpha | Deploys the Admiral agent  |
| [admiral-server](https://github.com/DataliftHQ/admiral-helm/tree/master/charts/admiral-server) | Alpha | Deploys the Admiral server |

## Security Policy

Please refer to [SECURITY.md](https://github.com/DataliftHQ/admiral-helm/blob/master/SECURITY.md) for details on how to report security issues.

## Changelog

Releases are managed independently for each helm chart, and changelogs are tracked on each release.
