Lab1

1)minikube start

2)prometheus operator installed:

i)helm repo add prometheus-community https://prometheus-community.github.io/helm-charts

ii)helm repo update

iii)helm install monitoring prometheus-community/kube-prometheus-stack -n monitoring --create-namespace

3)Access prometheus

kubectl port-forward svc/prometheus-operated -n monitoring 9090:9090

<img width="940" height="487" alt="image" src="https://github.com/user-attachments/assets/5f08aaf0-2510-4e14-910a-9986309ddd13" />

4)PromQL queries:

UP:

<img width="940" height="441" alt="image" src="https://github.com/user-attachments/assets/b3c899ac-6728-4a29-91bf-0c49e84a91cd" />

CPU Usage:

<img width="940" height="412" alt="image" src="https://github.com/user-attachments/assets/a2008f1d-9d67-48b0-a00c-a4e071ec6a1e" />

Pods Phase:

<img width="940" height="474" alt="image" src="https://github.com/user-attachments/assets/aadebf19-1ac8-4325-ba40-0ef95920c6ca" />

Running Pods:

<img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/38b4c4fe-924c-489a-871b-f5dc470a5ec6" />

pods that are not Running:

<img width="940" height="472" alt="image" src="https://github.com/user-attachments/assets/7a86528d-d8e2-4067-803a-7c078434363c" />

Lab2

<img width="938" height="270" alt="image" src="https://github.com/user-attachments/assets/e72da310-6b5c-4353-b91f-bfe4511975f2" />

<img width="940" height="345" alt="image" src="https://github.com/user-attachments/assets/0b1ecd54-9731-4ab3-9753-5fbc24be8903" />








