# openconnect-sso

このプロジェクトは[vlaci/openconnect-sso](https://github.com/vlaci/openconnect-sso)からフォークされています。

PyQt6対応済みです。
必要の無いファイルは削除しました。



### Build

buildをインストールします。

```shell
$ pip3 install build
```

`pyproject.toml`と同じディレクトリで以下を実行します。

```shell
$ python3 -m build
```

dist配下に`openconnect_sso-X.X.X-py3-none-any.whl`と`openconnect-sso-X.X.X.tar.gz`が生成されます。



### Install

dist配下で以下を実行します。

```shell
$ pip3 install openconnect_sso-X.X.X-py3-none-any.whl
```



### Update

dist配下で以下を実行します。

```shell
$ pip3 install -U openconnect_sso-X.X.X-py3-none-any.whl
```


### Usage

[vlaci/openconnect-sso](https://github.com/vlaci/openconnect-sso)を参考にしてください。
