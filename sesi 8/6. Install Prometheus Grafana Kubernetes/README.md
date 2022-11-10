## Install Prometheus Grafana On Kubernetes

Tambahkan repo prometheus community
```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
```

Update 

```
helm repo update
```

Install Prometheus Grafana menggunakan helm
```
  helm install prometheus prometheus-community/kube-prometheus-stack --namespace monitoring --create-namespace
```

Default Login grafana dashboard

```
username: admin
password: prom-operator
```

