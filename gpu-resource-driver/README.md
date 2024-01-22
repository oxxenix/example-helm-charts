# Dynamic Resource Allocation (DRA) GPU Driver Helm Chart

## Install Helm Chart

Install CRDs as part of the chart:
```
kubectl apply -f ../../static/crds/
```

```
helm install intel-dra-gpu-resource-driver ./ \
--create-namespace --namespace intel-gpu-resource-driver
```

## Upgrade Chart
```
helm upgrade intel-dra-gpu-resource-driver ./
```

## Uninstall Chart
```
helm uninstall intel-dra-gpu-resource-driver
```