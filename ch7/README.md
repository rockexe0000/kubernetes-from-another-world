







```
### 建立/更新 deployment
kubectl apply -f ./deployment.yaml

### 建立/更新 deployment,並記錄更新歷史
kubectl apply -f ./deployment.yaml --record

### 指令更新 deployment
kubectl scale deployment bar-deployment --replicas=3

### 直接修改 deployment
kubectl edit deployment bar-deployment

### 查看 bar-deployment 狀態
kubectl rollout status deployment bar-deployment

### 查看 bar-deployment 歷史版本
kubectl rollout history deployment bar-deployment

### 查看 bar-deployment 指定歷史版本的詳細資訊
kubectl rollout history deployment bar-deployment --revision=2


#### 回滾到上一個版本
kubectl rollout undo deployment bar-deployment

### 回滾到指定版本
kubectl rollout undo deployment bar-deployment --to-revision=1

### 刪除 deployment
kubectl delete -f ./deployment.yaml


```










