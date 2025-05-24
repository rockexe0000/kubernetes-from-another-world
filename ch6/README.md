




### build & tag & push docker image
```

### ref: ../ch5/README.md

docker build --platform linux/amd64 -f Dockerfile -t bar .

docker tag bar rockexe0000/bar

docker push rockexe0000/bar

```



```
### 建立/更新 pod & services
kubectl apply -f pod.yaml,service.yaml

### 刪除 pod & services 
kubectl delete -f pod.yaml,service.yaml

```


```
curl http://localhost:8000
```




