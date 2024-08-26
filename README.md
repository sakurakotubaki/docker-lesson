# Dockerとは？
コンテナ仮想化技術を使って、アプリケーションを開発・配置・実装するためのツール

コンテナとは何か？
ホストマシンで動く。ホストOSで動く。Jboyだと自分のMac
コンテナがあると、ホストOSと干渉しない環境を作る

コンテナは、ホストマシンの上で、複数のコンテナを持つことができる。

[こちらを参考にする](https://github.com/JboyKingdom/docker-tutorial)


### Docker command
Enter the container
```shell
docker container run -it ubuntu:20.04
```

### Exit from the container
```shell
exit
```

### Dockerイメージとは？
配布＆コンテナの再現可能
イメージは、変更不可な静的テンプレート。
どの環境で実行しても同じコンテナ環境が再現できる。

### DockerHub
Dockerイメージを登録・配布可能なサイト。

[official](https://hub.docker.com/)