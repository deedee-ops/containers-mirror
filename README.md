# Container Images Mirror

Stop-gap container registry mirror of upstream applications that only use Docker Hub

## Purpose

This is to get around Docker Hub rate-limiting (100 pulls / 6 hours, or authenticated 200 pulls / 6 hours). It is considered a stop-gap until the maintainers of the applications below support a different Container Registry.

## Supported images

When upstream maintainers add support for an additional registry, the images here will be purged after awhile.

| Name                                                                                        | Upstream Issue                                                                                                                                                                                     |
|---------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [adguardhome](https://github.com/AdguardTeam/AdGuardHome)                                   | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/AdguardTeam/AdGuardHome/5975)](https://github.com/AdguardTeam/AdGuardHome/issues/5975)                                   |
| [echo-server](https://github.com/ealenn/Echo-Server)                                        |                                                                                                                                                                                                    |
| [gitea](https://github.com/go-gitea/gitea)                                                  | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/go-gitea/gitea/22922)](https://github.com/go-gitea/gitea/issues/22922)                                                   |
| [gitea-act\_runner](https://gitea.com/gitea/act_runner)                                     | [Gitea issue status](https://gitea.com/gitea/act_runner/issues/165)                                                                                                                                |
| [gluetun](https://github.com/qdm12/gluetun)                                                 |                                                                                                                                                                                                    |
| [gotenberg](https://github.com/gotenberg/gotenberg)                                         |                                                                                                                                                                                                    |
| [hivemq-platofrm-operator](https://github.com/hivemq/hivemq-platofrm-operator)              |                                                                                                                                                                                                    |
| [hivemq-platofrm-operator-init](https://github.com/hivemq/hivemq-platofrm-operator-init)    |                                                                                                                                                                                                    |
| [hivemq4](https://github.com/hivemq/hivemq4)                                                |                                                                                                                                                                                                    |
| [imapsync](https://github.com/imapsync/imapsync)                                            |                                                                                                                                                                                                    |
| [intel-deviceplugin-operator](https://github.com/intel/intel-device-plugins-for-kubernetes) | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/intel/intel-device-plugins-for-kubernetes/633)](https://github.com/intel/intel-device-plugins-for-kubernetes/issues/633) |
| [intel-gpu-plugin](https://github.com/intel/intel-device-plugins-for-kubernetes)            | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/intel/intel-device-plugins-for-kubernetes/633)](https://github.com/intel/intel-device-plugins-for-kubernetes/issues/633) |
| [nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager)             |                                                                                                                                                                                                    |
| [omada-controller](https://github.com/mbentley/docker-omada-controller)                     |                                                                                                                                                                                                    |
| [piped](https://github.com/TeamPiped/Piped-Backend)                                         |                                                                                                                                                                                                    |
| [piped-frontend](https://github.com/TeamPiped/Piped)                                        |                                                                                                                                                                                                    |
| [piped-proxy](https://github.com/TeamPiped/piped-proxy)                                     |                                                                                                                                                                                                    |
| [portainer](https://github.com/portainer/portainer)                                         | [![Github issue status](https://img.shields.io/github/issues/detail/state/portainer/portainer/4652)](https://github.com/portainer/portainer/issues/4652)                                           |
| [system-upgrade-controller](https://github.com/rancher/system-upgrade-controller)           |                                                                                                                                                                                                    |

## Docker OSS Program

Certain containers may not be rate limited if they are in Docker Hub's OSS Program or verified publishers. Below is a list of applications which appears to be part of this program.

- bitnami/*
- grafana/*
- intel/intel-deviceplugin-operator
- intel/intel-gpu-plugin
- nodered/node-red
- rook/ceph

Even though most of them can be fetched from different sources (like bitnami or rook-ceph), the ones which are not available, still may be monitored here.
