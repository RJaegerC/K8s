## 📌 Descrição

Este repositório demonstra o uso do Kubernetes na prática, utilizando o Minikube para criar um ambiente local de cluster dentro de uma máquina virtual Linux.
Por meio de arquivos YAML, foram configurados pods com todos os contextos necessários para criar um ambiente de cluster dentro do minikube.

## ⚙️ Configurações

Foram utilizados:
-Minikube (Ferramenta para aplicar kubernetes)
-Kubectl (CLI para gerenciamento do Kubernetes)
-Lens IDE (Gui para gerenciamento do cluster)
-Qemu (Virtualização para criação da VM Linux)

## 🛠 comandos importantes

minikube start \ 
--driver=qemu \
--network=mynet \
--memory=8000
--cpus=4

minikube status

kubectl get pod -n  

kubectl describe ubuntu -n 

kubectl delete pod ubuntu -n 

kubectl exec -it ubuntu -n 

kubectl apply -f pod/ubuntu-pod.yaml

kubectl delete -f

minikube addons list 

minikube addons enable

<img width="600" height="315" alt="lenside" src="https://github.com/user-attachments/assets/01511725-826a-4b34-83d7-57e0ec0ef925" />
