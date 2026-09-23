# Graylog Sidecar

Installs Graylog Sidecar and Metricbeat, then configures Metricbeat to send
system metrics to Graylog. Set `graylog_server_url`, `graylog_server_api_token`,
and `graylog_logstash_host` in encrypted inventory or group variables. Optional
`sidecar_tags` adds Graylog Sidecar tags.

Do not commit the Sidecar API token or private endpoint values.