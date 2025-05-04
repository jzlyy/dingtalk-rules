# prometheus-family
[![GitHub License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Integrate the entire Prometheus ecosystem to build a comprehensive black-box and white-box monitoring system, and enable rapid alert response through DingTalk robots.


## Binary
1. Integrate official Prometheus binaries including prometheus, node_exporter, alertmanager, blackbox_exporter, as well as the community-developed prometheus-webhook-dingtalk binary by timonwong.  
2. Implement centralized deployment using systemd to achieve lightweight, efficient, and rapid configurationintegration, with DingTalk robot-enabled fast alert response capabilities.  
3. Establish a comprehensive Prometheus monitoring system through black-box and white-box monitoring solutions to maximize resource responsiveness.

## Kubernetes(Helm)
1. Integrate official kube-prometheus-stack, prometheus-adapter, and prometheus-blackbox-exporter Helm charts to build a complete Prometheus monitoring system in Kubernetes environment.  
2. Utilize Prometheus-Operator to achieve fine-grained isolation of monitoring scenarios and automated management of ServiceMonitor, PodMonitor, and ProbeMonitor resources.  
3. Implement blackbox/whitebox monitoring solutions in Kubernetes environment with DingTalk robot integration, enabling rapid response to resource alerts.

## Start
The team can refer to my code solution and make reasonable modifications based on specific environmental requirements.

## Security Policy
To report security vulnerabilities, please see [SECURITY.md](SECURITY.md)。
