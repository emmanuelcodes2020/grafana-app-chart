# grafana-app-chart

This Helm chart deploys the Grafana application on a EKS Cluster

Prerequisites:
1) EKS Cluster (AWS) : must be set up first 
2) Helm must be created with the "helm create repo"



## Installing the Chart

To install the chart with the release name : grafana-app-release

```

helm install grafana-app-release  ./grafana-app-chart

```


## Upgrading your Chart

To upgrade the chart with the release name : grafana-app-release

```

helm upgrade grafana-app-release  ./grafana-app-chart

```

## Installing the Chart with values.yaml

To install the chart with the release name : grafana-app-release 

```

helm install grafana-app-release ./grafana-app-chart   --Values ./grafana-app-chart/values.yaml

```



## Uninstalling the Chart

To uninstall the grafana-app-release deployment:

```

helm uninstall grafana-app-release   ./grafana-app-chart

```

