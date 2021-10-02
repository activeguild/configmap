# configmap
https://www.google.co.jp/amp/s/kakakakakku.hatenablog.com/entry/2020/08/25/091308%3famp=1
https://blog.mosuke.tech/entry/2019/06/21/kustomize/
https://tech.recruit-mp.co.jp/infrastructure/post-20439/
https://kubernetes.io/ja/docs/reference/kubectl/cheatsheet/

# command
```
minikube start
kubectl get configmap
kubectl get configmap test-json -o json
kubectl get pods -l app=nginx
kubectl apply -f ./base/deployment.yaml
kubectl delete deployment nginx-deployment
kubectl apply -k ./
kubectl exec nginx-deployment-749d88f8ff-8x8xl  -- cat /etc/config/test.json
```