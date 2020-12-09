# Prometheus 

## 部署
```shell
cd dev_tool/prometheus

# 启动 metrics-server
kubectl apply -f metrics-server/.

# 启动 prometheus
kubectl apply -f prometheus/.
``` 