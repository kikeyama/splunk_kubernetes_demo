# Splunk Demo App for Kubernetes
## What is it?
This Splunk app includes dashboards and configurations. It enables visualization of Kubernetes clusters and containers, real-time monitoring, and troubleshooting.

## Expected Use Case
**IT operation** and **DevOps**
* Kubernetes Resources (Nodes / Namespaces / Services / Pods etc)
* Monitoring Repliication Health
* Monitoring Kubernetes Controller Manager Logs
* Monitoring Kubelet Logs and Container Logs
* Monitoring Metrics

## How to setup?
1. Install **Splunk Add-on for Kubernetes** on your Splunk Deployment/Cluster.
2. Then ingest data via **Splunk Connect for Kubernetes** from your k8s cluster to Splunk Cluster.
3. Enter your indexes into macros `k8s-event-index` and `k8s-metrics-index` in **Splunk Add-on for Kubernetes**.
4. Install this demo app on your Splunk.
**Install this app only in Search Head (Not required for IDX or FWD)**

**Splunk Add-on for Kubernetes**  
https://splunkbase.splunk.com/app/3991/

**Splunk Connect for Kubernetes**  
https://github.com/splunk/splunk-connect-for-kubernetes

Splunk Add-on for KubernetesとSplunk Connect for Kubernetesのセットアップ方法はこちら（Japanese Only）  
**SplunkでKubernetesのログとメトリクスを監視してみよう**  
https://qiita.com/kikeyama/items/447c7126a5c454a558f0
