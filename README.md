# 北海道老人保健施設協議会様
## https://doroken.jp

最終更新日：2023.9.12  
北海道老人保健施設協議会様の公式WEBサイトドキュメントです。  
主にサイト構造や変更方法・公開方法等を記載しております。 

## インストール方法
1. docker環境を用意する
2. GitHubリポジトリから「doroken」リポジトリをCloneする

## 開発の仕方
1. GitHubのブランチがmasterかどうかを確認する
2. エディタでpackages内のファイルを修正する
3. ブラウザで確認する
4. masterブランチにコミットする

```
http://localhost:8000
```


## デプロイ方法
SFTPで直接アップロードします。

## cssのコンパイル

```
npm run scss
```

## テスト



## インフラ・開発環境等の仕様
- ドメイン：muumuuドメイン
- WEBサーバー：Xserver
- メールサーバー：Xserver
- SSL：無料SSL証明書 Let's Encrypt
- リポジトリ：GitHub
- CI：なし
- デプロイ：deplyer
- データベース：MySQL
- 開発環境構築：Local
- 言語・FW等：WordPress
- その他：SCSSコンパイル,minify等

## Author
[caresurveyjapan Co.,Ltd](https://caresurvey.co.jp)


