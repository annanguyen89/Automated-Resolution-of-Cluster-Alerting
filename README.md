#Automated-Resolution-of-Cluster-Alerting
##Overview
The Automated Resolution of Cluster Alerting project is a solution designed to monitor and handle Kubernetes cluster alerts by automatically detecting, analyzing, and providing resolutions for errors. This is achieved through the integration of Kibana, Prometheus, and ChatGPT for real-time log filtering and automated error resolution, with notifications and collaboration through Slack.

##Key Features:
* Log Collection and Parsing: Aggregates logs and metrics from Kubernetes applications, infrastructure, and services using Elastic Cloud on Kubernetes (ECK).
* Error Detection and Filtering: Uses Kibana and Prometheus to filter and retrieve logs based on error severity.
* Automated Error Resolution: Integrates ChatGPT to provide comprehensive solutions for identified errors.
* Slack Integration: Sends alert notifications and error resolution recommendations to Slack channels for collaboration and prompt action.
