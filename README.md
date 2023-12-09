# Container Images Mirror

Stop-gap container registry mirror of upstream applications that only use Docker Hub

## Purpose

This is to get around Docker Hub rate-limiting (100 pulls / 6 hours, or authenticated 200 pulls / 6 hours). It is considered a stop-gap until the maintainers of the applications below support a different Container Registry.

## Supported images

When upstream maintainers add support for an additional registry, the images here will be purged after awhile.

| Name                                                                                        | Upstream Issue                                                                                                                                                                                     |
|---------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [gitea](https://github.com/go-gitea/gitea)                                                  | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/go-gitea/gitea/22922)](https://github.com/go-gitea/gitea/issues/22922)                                                   |
| [gotenberg](https://github.com/gotenberg/gotenberg)                                         |                                                                                                                                                                                                    |
| [intel-deviceplugin-operator](https://github.com/intel/intel-device-plugins-for-kubernetes) | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/intel/intel-device-plugins-for-kubernetes/633)](https://github.com/intel/intel-device-plugins-for-kubernetes/issues/633) |
| [intel-gpu-plugin](https://github.com/intel/intel-device-plugins-for-kubernetes)            | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/intel/intel-device-plugins-for-kubernetes/633)](https://github.com/intel/intel-device-plugins-for-kubernetes/issues/633) |

## Docker OSS Program

Certain containers may not be rate limited if they are in Docker Hub's OSS Program or verified publishers. Below is a list of applications which appears to be part of this program.

- bitnami/*
- grafana/*
- intel/intel-deviceplugin-operator
- intel/intel-gpu-plugin
- nodered/node-red
- rook/ceph

Even though most of them can be fetched from different sources (like bitnami or rook-ceph), the ones which are not available, still may be monitored here.
