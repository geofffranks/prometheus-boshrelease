### Features

* Allow setting custom headers in nginx config
* Allow `kube-state-metrics` to get properties from [cfcf](https://docs-cfcr.cfapps.io/)
* Allow `kube-state-metrics` to use a proxy
* Allow `prometheus` to use a proxy
* Updated `kubernetes` dashboards

### Manifests

* `monitor-kubernetes` op file now enables kubernetes API servers and kubelets service discovery
* Added op files to enable proxy properties on several components
* Bump `cf-routing` release to [v0.172.0](https://github.com/cloudfoundry/routing-release/releases/tag/0.172.0)
* Bump `postgres` relase to [v26](https://github.com/cloudfoundry/postgres-release/releases/tag/v26)

### Upgrades

* `alertmanager` to [v0.14.0](https://github.com/prometheus/alertmanager/releases/tag/v0.14.0)
* `blackbox_exporter` to [v0.12.0](https://github.com/prometheus/blackbox_exporter/releases/tag/v0.12.0)
* `cf_exporter` to [v0.6.2](https://github.com/bosh-prometheus/cf_exporter/releases/tag/v0.6.2)
* `firehose_exporter` to [v5.0.2](https://github.com/bosh-prometheus/firehose_exporter/releases/tag/v5.0.2)
* `grafana` to [v5.0.4](https://github.com/grafana/grafana/releases/tag/v5.0.4)
* `kube-state-metrics` to [v1.2.0](https://github.com/kubernetes/kube-state-metrics/releases/tag/v1.2.0)
* `memcached_exporter` to [v0.4.1](https://github.com/prometheus/memcached_exporter/releases/tag/v0.4.1)
* `prometheus` to [v2.2.1](https://github.com/prometheus/prometheus/releases/tag/v2.2.1)
* `rabbitmq_exporter` to [0.26.0](https://github.com/kbudde/rabbitmq_exporter/releases/tag/v0.26.0)
* `redis_exporter` to [0.17.1](https://github.com/oliver006/redis_exporter/releases/tag/v0.17.1)
* `stackdriver_exporter` to [v0.5.1](https://github.com/frodenas/stackdriver_exporter/releases/tag/v0.5.1)
