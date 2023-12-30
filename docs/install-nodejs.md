# Node.js（とついでにyarn）をインストールする

## 推奨方法

[Volta](https://volta.sh/) を使ってNode.jsをインストールします。VoltaはJavaScriptのツールマネージャーで、簡単にNode.jsをインストールできます。

[公式ページ](https://docs.volta.sh/guide/getting-started) を参考にインストールします。

```bash
# voltaをインストール
$ curl https://get.volta.sh | bash

# シェルを再起動
$ exec $SHELL -l

# Node.jsをインストール（バージョン指定しない場合は最新LTSが入る）
$ volta install node

# yarnをインストール（バージョン1指定）
$ volta install yarn@1

# Node.jsとyarnがインストールされたことを確認
$ volta list
⚡️ Currently active tools:

    Node: v20.10.0 (default)
    Yarn: v1.22.21 (default)
    Tool binaries available: NONE
```

## 他のインストール方法

### Node.js公式ページからインストールする

[こちら](https://original-game.com/how-to-install-node-js-on-mac/) を参考に [Node.js公式ページ](https://nodejs.org/en/download) からダウンロードしてください。

### Windowsの方

[WindowsでNode.jsをインストールしよう！ (nvm-windows)](https://zenn.dev/y_2_k/articles/e419bcf729e82d) を参考にインストールしてください。