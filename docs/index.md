# 社内向け git trainig

- ローカル: 作業端末(PC)内
- リモート: github

## 設定(ファイル)変更
```
$ git config --global <attr> <value>
```
- --globalをつける: 当該ユーザのシステム全体の設定(~ /.gitconfig)
- --globalをつけない: 実行したリポジトリ独自の設定(.git/config)

### gitユーザ設定
- ローカル(作業端末)にユーザ情報をセットする
- Gitの設定ファイル更新
```
git config --global user.name "USER NAME"
git config --global user.emal "USER Email"
``` 

- 設定の確認
```
$ git config --global --list
user.name=hoge
user.email=hoge@gmail.com
```
