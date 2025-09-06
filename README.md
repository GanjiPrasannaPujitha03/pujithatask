Lab1
1)minikube start

2)prometheus operator installed:

i)helm repo add prometheus-community https://prometheus-community.github.io/helm-charts

ii)helm repo update

iii)helm install monitoring prometheus-community/kube-prometheus-stack -n monitoring --create-namespace

3)Access prometheus

kubectl port-forward svc/prometheus-operated -n monitoring 9090:9090

<img width="940" height="487" alt="image" src="https://github.com/user-attachments/assets/5f08aaf0-2510-4e14-910a-9986309ddd13" />
