# lpic-305

# [ping-t] コマ問プレミアムLPIC Lv3-305(Ver3.0)

## Docker 1

| 問題 | 回答 |
| ---- | ---- |
| dockerコマンドにおいて、起動中のコンテナへログインするサブコマンドは？ | `attach` |
| Dockerのコンテナごとの設定やイメージ、ログなどが配置されたディレクトリは？（フルパス） | /var/lib/docker/ |
| Dockerのデーモンdockerdのオプションをカスタマイズするファイルは？（フルパス） | /etc/docker/daemon.json |
| docker create、docker runコマンドにおいて、既に存在するコンテナのボリューム構成を再利用するオプションは？ | `--volumes-from` |

## Docker 2

| 問題 | 回答 |
| ---- | ---- |
| Dockerfileにおいて、作業ディレクトリを指定する命令は？ | `WORKDIR` |
| Dockerfileにおいて、作成者やバージョン情報などのメタデータを指定する命令は？ | `LABEL` |
| 以下のDockerfileで、コンテナ起動時に「Hello, Docker」と出力させたい。CMDコマンドによる命令を、シェル形式とexec形式で答えよ。 <br>![koma-mon Docker2 Q.09](./images/koma-mon-docker2-q09.png) | **シェル形式：** `CMD echo "Hello, Docker"` <br> **exec形式：** `CMD [ "echo", "Hello, Docker" ]` |
| 以下のDockerfileで、コンテナ起動時に「Hello, Docker」と出力させたい。ENTRYPOINTコマンドによる命令を、シェル形式とexec形式で答えよ。 <br>![koma-mon Docker2 Q.11](./images/koma-mon-docker2-q11.png) | **シェル形式：** `ENTRYPOINT echo "Hello, Docker"` <br> **exec形式：** `ENTRYPOINT [ "echo", "Hello, Docker" ]` |
| Dockerfileにおいて、作成するマウントポイントを指定する命令は？ | `VOLUME` |

## コンテナオーケストレーションプラットフォーム

| 問題 | 回答 |
| ---- | ---- |
| 次の特徴を持つコンテナオーケストレーションプラットフォームは？ <br> ・「Run Kubernetes Everywhere」をコンセプトに開発された <br>  ・複数のKubernetesクラスタを一元的に構築・管理するKubernetesの管理ツール | Rancher |
| 次の特徴を持つコンテナオーケストレーションプラットフォームは？ <br> ・Apache Mesosをベースとし、エンタープライズ向けに開発された <br> ・データセンター全体を一つのOSとみなして制御できるよう設計された | Mesosphere DC/OS |
