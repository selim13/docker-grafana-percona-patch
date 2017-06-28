An [Grafana 3 image](https://hub.docker.com/r/grafana/grafana/) patched for use with 
[mysqld_exporter](https://github.com/prometheus/mysqld_exporter) and enabled JSON dashboards.

See [Grafana dashboards](https://github.com/percona/grafana-dashboards) repository by Percona for
the additional information about patch.

# Deprecation

This image is frozen with Grafana 3.0.4 as a base image: the patch 
is [broken](https://github.com/grafana/grafana/issues/5750) for Grafana 3.1.1
and was [merged](https://github.com/grafana/grafana/pull/5839) to the official
Grafana 4.