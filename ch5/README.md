




### build & run docker image
```
docker build --platform linux/amd64 -f Dockerfile -t foo .

docker run --rm -p 8080:8080 -it -d foo

docker tag foo rockexe0000/foo

docker push rockexe0000/foo

```


### run pod
```
### 建立/更新 pod
kubectl apply -f pod.yaml

### 列出 pod
kubectl get pods

### 列出 pod 詳細資訊
kubectl describe pod foo

### pod 的 8080 port 轉發到 localhost 的 8080 port
kubectl port-forward pod/foo 8080:8080

```












