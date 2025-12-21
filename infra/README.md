\# Infrastructure Setup



\## Cluster

\- Local Kubernetes cluster using k3d

\- 1 server, 2 agents



\## Monitoring

\- Prometheus configured to scrape Decision Engine

\- Grafana dashboard placeholder added



\## Run

```bash

k3d cluster create --config infra/k3d/cluster.yaml

kubectl apply -f infra/monitoring/prometheus.yaml

"# Infra setup"

