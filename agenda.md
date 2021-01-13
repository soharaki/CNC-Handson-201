# Day 1

## イントロダクション

- チームの紹介
- 講師
- このコースの目的
- 参加者への案内
---

## コンテナ及びDockerの基礎

### 仮想化技術の目的

- リソースをいかに効率よく使用するか
- セキュリティを担保した環境の構築

### コンテナの技術史

- chroot
- namespaces
- cgroup
- docker

### コンテナはどうやって動くのか？

- コンテナイメージの形式
- Dockerfile
- コンテナランタイムとイメージレジストリサーバー
- コンテイメージのビルド方法

---

### ハンズオン環境

- ハンズオン環境へのアクセス方法
  - SSH鍵の登録方法
  - SSH to one of the nodes
- コンテナをビルド、プッシュ、そして動かしてみよう

---

## Kubernetes(クーバーネティス)の基礎

### Kubernetesの背景

- 歴史
- コンセプト

### Kubernetesのアーキテクチャ

- クラスタ
- ノード
- 鍵となるコンポーネント

### Kubernetesのリソース

- Pod
- Service
- Deployment

---

### ハンズオン: Kubernetes環境へのデプロイ

- Kubernetesクラスタへアクセスする
- アプリケーションをデプロイしてみよう

---

## CI/CD

- k8s上のCI/CD ベーシックコンセプト
- パイプラインデザインのベストプラクティス

### ハンズオン: simple CI/CD

---
Q&A, Free lab

---

# Day 2

---
## Kubernetes workloadのためのパッケージリソース

Kubernetes workloadとはKubernetes上にコンテナを起動するために利用するリソースを指します。要はPodやDeploymentのことです。
Kubernetes workloadのためのパッケージリソースとは、PodやDeploymentを複数まとめてデプロイするためのパッケージ管理用リソースを指します。

- Helm
- kustomize
- Operator


- Monitoring Kubernetes

- Prometheus/Grafana
- Thanos

### ハンズオン: k8s上の運用をサポートするツールのデプロイ

- Deploy Prometheus/Grafana

---

### ハンズオン: Operatorを使ったアプリケーションのデプロイ
