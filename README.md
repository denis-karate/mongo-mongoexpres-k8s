helm repo add bitnami https://charts.bitnami.com/bitnami

helm repo update

helm install my-mongodb bitnami/mongodb -f values-mongodb-for-helm.yaml
