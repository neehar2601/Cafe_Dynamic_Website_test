# Cafe_Dynamic_Website

## Directory Structure
CafeApp/ ├── Chart.yaml # Metadata about the Helm chart ├── values.yaml # Default values for the chart ├── templates/ # Directory containing Kubernetes manifests ├── deployment.yaml # Deployment resource for the CafeApp ├── service.yaml # Service resource for exposing the CafeApp ├── pv-pvc.yaml # PersistentVolume and PersistentVolumeClaim configuration ├── gateway.yaml # Istio Gateway configuration ├── virtualservice.yaml # Istio VirtualService configuration ├── destinationrule.yaml # Istio DestinationRule configuration ├── canary.yaml # Flagger Canary configuration
