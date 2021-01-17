## kindでk8sクラスタの起動
```
kind create cluster --config kind.yml --name kindcluster
```

## Contextの切り替え
```
kubectl config use-context kind-kindcluster
```

## ノードの確認
```
kubectl get nodes
```

## Dockerコンテナの確認
```
docker container ls
```

## kindクラスタの停止
```
kind delete cluster --name kindcluster
```
