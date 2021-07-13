# prometheus-grafana-influxdb-monitoring-stack
prometheus-grafana-influxdb-monitoring-stack


Installation and usage
From the root directory of this repo, run the command below:

$ docker-compose up -d

Grafana Data Source set up
In order to reach the Prometheus container, it is needed to create a Prometheus Data Source with the proper URL in Grafana:

URL: http://localhost:9090

URL: http://localhost:3000