1) build the project with maven
2) docker build -t springboot-k8s-example:1.0 .
3) kubectl apply -f deployment.yaml
4) kubectl apply -f service.yaml

5)
kubectl get service
NAME                          TYPE        CLUSTER-IP      EXTERNAL-IP   PORT(S)          AGE
springboot-k8s-svc            NodePort    10.98.212.91    <none>        8080:32426/TCP   2m3s

6)
kubectl get nodes -o wide
NAME       STATUS   ROLES           AGE     VERSION   INTERNAL-IP    EXTERNAL-IP   OS-IMAGE             KERNEL-VERSION      CONTAINER-RUNTIME
minikube   Ready    control-plane   7d14h   v1.24.1   192.168.49.2   <none>        Ubuntu 20.04.4 LTS   5.15.0-41-generic   docker://20.10.17

7)
minikube ip
192.168.49.2

8)
get to http://192.168.49.2:32426/message

output:
Congratulation you successfully deployed your application to kubernetes !!
