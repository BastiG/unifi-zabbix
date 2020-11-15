# unifi-zabbix

Use this template to gather metrics from a UniFi DreamMachine (Pro) in Zabbix.
Metrics collection heavy lifting is done by UnifiPoller (https://github.com/unifi-poller/unifi-poller).
Highly recommended and convenient: https://hub.docker.com/r/golift/unifi-poller

The following macros are supported by the template:
{$UDM.NAME} - the name of your DreamMachine (Pro) as it appears in the Prometeus metrics
{$UDM.EXPORTER_URL} - the URL of the metrics exporter, defaults to http://127.0.0.1:9130/metrics which again is the defaults for the Docker container.
