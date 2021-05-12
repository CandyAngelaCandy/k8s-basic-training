1. kubectl apply -f pod.yaml --validate=false
2. kubectl get pod node-express -o yaml      
3. kubectl cluster-info  
   查看集群的信息
4. kubectl get nodes
   查看运行的node
5. 概念就是context。context决定kubectl与哪个cluster交互。
   可以在~/.kube/config中查看。通过以下指令指定context。   
   kubectl config use-context minikube
6. kubectl version --short
   查看kubectl的版本
7. kubectl api-versions
   查看api的version
8. kubectl version --client
9. kubectl get pods -o wide -l 'app=node-express'
   获取deployment的所有pod信息
10. kubectl get deploy node-express-deployment
   查看Deployment 状态
11.  kubectl get svc nginx-service -o wide
   查看service的状态
12.  kubectl get ingress -o wide   
   

   
   
   

