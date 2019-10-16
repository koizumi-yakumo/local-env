# local-env

ローカル開発環境構築用のリポジトリ

## 利用開始手順

1. homebrew のインストール
    * [Homebrew](https://brew.sh/) を確認
1. ansible のインストール
    * brew install ansible

## 実行手順

```
ansible-playbook -i inventory main.yml
```