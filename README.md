# my-macbook
MacBookを買ったときの初期設定

# 使い方
## Homebrewのインストール

```sh
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

```

## Ansibleのインストール
```sh
$ brew install ansible
```

## Gitのインストールと、このリポジトリのダウンロード
```
$ brew install git
$ git clone git@github.com:genkami/my-macbook.git
```

## Playbookの適用

```
$ cd my-macbook
$ ansible-playbok 
```

