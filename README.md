In `my-chart/values.yaml`, what should replace `WHAT-GOES-HERE` such that the Grafana source correctly references the service name of the InfluxDB chart?

If it were a template, I could use `{{ .Release.Name }}-influxdb`, but value overrides are not templatable.
