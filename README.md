# k8sでのcommnadとargsの挙動についてのサンプル

このリポジトリは、Qiita記事 [k8sでのcommnadとargsの挙動について](https://qiita.com/maaaashi/items/fd5e7a212eb8e4622f40) に基づいたサンプルコード集です。

## 使用方法

### Docker

Dockerがインストールされた環境で以下の手順を実行してください。

```bash
$ docker build -t echo .
$ docker run -it --rm echo
```

### Kubernetes

kubectlがインストールされた環境で以下の手順を実行してください。

```bash
$ kubectl apply -f manifest.yaml
$ kubectl logs echo
```

##

詳しい解説は以下の記事をご覧ください。

👉 Qiita: [k8sでのcommnadとargsの挙動について](https://qiita.com/maaaashi/items/fd5e7a212eb8e4622f40)