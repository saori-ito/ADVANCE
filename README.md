## Atte
会社の勤怠管理システム
<img width="1413" alt="スクリーンショット 2022-02-01 23 38 13" src="https://user-images.githubusercontent.com/86700967/151989728-f64177b8-b086-4606-91cc-d66ea4cf4450.png">
<img width="1408" alt="スクリーンショット 2022-02-01 23 38 22" src="https://user-images.githubusercontent.com/86700967/151989731-ecd48d4e-2d86-4ee2-b31d-53395ef8451d.png">
<img width="1414" alt="スクリーンショット 2022-02-01 23 35 16" src="https://user-images.githubusercontent.com/86700967/151989702-afe8386e-70a4-4f16-a0e2-82810fca4950.png">
<img width="1414" alt="スクリーンショット 2022-02-01 23 36 03" src="https://user-images.githubusercontent.com/86700967/151989718-cdd0e837-928f-4d4f-a832-53eb785011c9.png">
<img width="1410" alt="スクリーンショット 2022-02-01 23 36 31" src="https://user-images.githubusercontent.com/86700967/151989721-53d8d3cf-29fa-4099-aef5-cddc265605a8.png">
<img width="1410" alt="スクリーンショット 2022-02-01 23 37 01" src="https://user-images.githubusercontent.com/86700967/151989724-6ab215bd-aa96-4a1b-83fb-d36134292b44.png">

## 作成した目的
スクールの課題として取り組みました。模擬案件を通じて、実際の開発に近いものを体験します。

## 機能一覧
フロントエンド

・HTML/CSS

・JavaScript

・バックエンド

・PHP 7.4.23

・Laravel Framework 8.68.1

・Laravel breeze

・Mysql 5.7.32    

インフラ

・環境の切り分け

・テスト

・Docker

・Heroku

・ClearDB MySQL(Heroku)

# 環境を構築する方法

## MAMP / XAMPP
環境構築（Mac）

MAMPをインストールします

https://www.mamp.info/en/downloads/

環境構築（Windows）

XAMPPをインストールする

https://www.apachefriends.org/jp/index.html

## クローン
git clone https://github.com/yomogi-tyannneru/ADVANCE.git

## メール認証

```php
MAIL_DRIVER = smtp
MAIL_HOST = smtp.gmail.com
MAIL_PORT = 587
MAIL_USERNAME =自分のGmail
MAIL_PASSWORD =自分のアプリのパスワード
MAIL_ENCRYPTION = tls
MAIL_FROM_ADDRESS =自分のGmail
MAIL_FROM_NAME =任意のアプリ名
```

.envファイルを上記に変更します

○参考サイト

[https://zenn.dev/kazushino/articles/67da2015865ae117444c]（https://zenn.dev/kazushino/articles/67da2015865ae117444c）

## テスト
PHPUnitを使用してテストを作成する

vendor / bin / phpunitはテストコードです。

vendor / bin / phpunit tests / Feature / Auth / AuthenticationTest.phpは、認定のみのテストです。

## Docker
Dockerを使用して環境を構築する

Dockerのインストール（Mac）

https://www.docker.com/products/docker-desktop

Dockerのインストール（Windows）

https://hub.docker.com/editions/community/docker-ce-desktop-windows/

## 環境の切り分け
開発環境と本番環境の切り分けを行います。

## Heroku
https://lit-peak-96335.herokuapp.com/








