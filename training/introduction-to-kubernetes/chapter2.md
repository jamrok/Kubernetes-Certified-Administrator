# Chapter 2

Kubernetes についての説明。そもそもKubernetes 自体は Google で使用されているクラスタマネージャの Borg からできている。

## Objectives

- Kubernetes とはなにかについて理解する
- Kubernetes の機能について理解する

## Kubernetes とはなにか

```
"Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications."
```

Kubernetes のウェブサイトにかかれている文章。

Kubernetes は helmsman, ship pilot という意味。Docker コンテナを ship するところからきてる。

## Borg から Kubernetes へ

```
"Google's Borg system is a cluster manager that runs hundreds of thousands of jobs, from many thousands of different applications, across a number of clusters each with up to tens of thousands of machines."

```

Borg すごい。 Borgmon もすごい。

- API servers
- Pods
- IP-per-Pod
- Services
- Labels

などは Borg から来てる。

## Kubernetes の機能 1

- 自動 binpacking (コンテナの起動リソース選択とか)
- self-healing
- horizontal scaling
- サービスディスカバリと負荷分散

## Kubernetes の機能 2

- Rollout/Rollback
- secret management
- Storage orchestration
- Batch execution

バッチ機能とか嬉しい。

Roll-based access control(RBAC) とかももうすぐ。

## なぜ Kubernetes を使うのか

- とてもポータブル
  - いろんな環境で動く

## Kubernetes を使ってる企業

- Pearson
- Box
- eBay
- Huawei
などなど


