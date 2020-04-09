# Introduction

An experiment with K8 statefulset for InfluxDB deployment.

The statefulset is achieved by PVC on an EFS mount.

## Makefile
```
influxdb-stateful-chart upgrade/tiller   Upgrade tiller to the latest version.
influxdb-stateful-chart install          Deploy stack into kubernetes. vars: stack
influxdb-stateful-chart delete           delete stack from reference
influxdb-stateful-chart upgrade          upgrade the release
```
