# anyenvをインストールする

[anyenv](https://github.com/anyenv/anyenv) はさまざまなプログラミング言語のバージョンを管理するツールです。Node.jsの他にPythonやphp、Rubyといった

[anyenvをインストールする](https://zenn.dev/y__adler/articles/a64ad1b8dacc4c) を参考にanyenvをインストールしましょう。ここではbrewコマンドを使いますが、brewコマンドが未インストールの場合は [こちらの手順](./install-homebrew.md) を先に実施してください。

```bash
# brewコマンドでanyenvをインストール
$ brew install anyenv

# `anyenv init`を実行すると以下のように表示される
$ anyenv init
# Load anyenv automatically by adding
# the following to ~/.zshrc:

eval "$(anyenv init -)"

# 指示通り .zshrcファイルを開いて最後行に「eval "$(anyenv init -)"」を追記
$ open ~/.zshrc

# 追記し保存した後、sourceコマンドで設定反映
$ source ~/.zshrc

# anyenvを初期化
$ anyenv install --init
```
