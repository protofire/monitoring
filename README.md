# Monitoring Templates for Multi-Cloud Blockchains

- [Link to the article](https://medium.com/protofire-blog/protofire-releases-monitoring-templates-for-multicloud-blockchains-740b2b19127f)
- [Wiki](https://github.com/protofire/monitoring/wiki)

This repository contains configuration templates for all the tools described in our article [**"Protofire Releases Monitoring Templates for Multi-Cloud Blockchains"**](https://medium.com/protofire-blog/protofire-releases-monitoring-templates-for-multicloud-blockchains-740b2b19127f)

Setup instructions can be found in the [Wiki](https://github.com/protofire/monitoring/wiki) section of this repository

Directories description:

| Directory                    | Content                                                                        |
| ---------------------------- | ------------------------------------------------------------------------------ |
| aws-cloudwatch-agent-configs | Configuration files for AWS Cloudwatch Agent to gather basic instances metrics |
| grafana-dashboards-cloudwatch | Grafana JSON-dashboards to vizualize metrics collected with AWS CloudWatch Agent |
| grafana-dashboards-influxdb | Grafana JSON-dashboards to vizualize metrics collected with Telegraf and stored in InfluxDB |
| logstash | Everything you need to gather logs from different blockchain nodes with Logstash run as a docker container |
| telegraf | Basic and additional telegraf agent configuration files to gather metrics from different blockchain nodes and relayers |

We are looking forward to your feedback. Feel free to open [issues](https://github.com/protofire/monitoring/issues) and submit [pull requests](https://github.com/protofire/monitoring/pulls) to this repository

# License

[GPLv3](https://github.com/protofire/monitoring/blob/main/LICENSE)

# Authors

- [Arsenii Petrovich](https://github.com/ArseniiPetrovich)
- [Dzmitry Kliapkou](https://github.com/dzmitrykliapkou)
