# intel-device-plugins-helm-chart
Intel Device Plugins for Kubernetes

## Get Helm Repository Info
```
helm repo add intel-device-plugins https://obaranov1.github.io/helm-chart/
helm repo update
```

## Get Added Helm Charts [optional]
```
helm search repo intel-device-plugins
```

## Install Helm Chart
```
helm install [RELEASE_NAME] intel-device-plugins/intel-device-plugins-operator 
```

## Uninstall Chart
```
helm uninstall [RELEASE_NAME]
```

## Upgrade Chart
```
helm upgrade [RELEASE_NAME] intel-device-plugins/intel-device-plugins-operator [flags]
```
