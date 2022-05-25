# Esercitazione Kubernetes

# Requisiti
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [docker](https://docs.docker.com/get-docker/)
- [Lens](https://k8slens.dev/)

# Informazioni
Alcuni esempi di Deployment, Servizi, Secret e Pods in Kubernetes
 
# Comandi utili
kubectl create -f <nome-file>   //Crea un nuovo pod
kubectl get pods                //Recupera i pod in esecuzione
kubectl delete pod <nome-pod>   //Elimina il pod richiesto
kubectl apply -f <file-name>    //Applica una nuova configurazione ad un running pod
kubectl rollout history deployment <nome-deployment>	//Visualizza modifiche fatte con apply a un particolare deployment
kubectl rollout status deployment <nome-deployment>
kubectl rollout undo deployment <nome-deployment>
