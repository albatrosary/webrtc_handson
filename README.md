# webrtc_handson

このリポジトリはWebRTCのハンズオンを開催する為に必要なコードを管理するリポジトリです。

## 事前準備

#### ローカルサーバを立てられるように準備する

- Macの場合
```
python -m SimpleHTTPServer 8000
php -S localhost:8000
```

- Windowsの場合

XAMPP - http://www.adminweb.jp/xampp/


#### NodeJSが動かく環境を準備する

- MacとWindows共に `node` コマンド、 `npm` コマンドが使えるようにして下さい。


## STEP1

   - がねこさんの手動シグナリングを体感する
     - 目的：シグナリングのイメージを体感する
     - 動作ブラウザ：Chrome

## STEP2

   - 簡単なビデオチャットアプリを開発する
     - 目的：WebRTCのAPIの使い方を知ってもらう
     - 動作ブラウザ：Chrome
     - シグナリングサーバ：nodejsによる簡易版をソースコード提供

## STEP3

   -  SkyWayを使ってビデオチャットを作る
      - 目的：SkyWayを使うと簡単に開発できることを体感してもらう
      - 動作ブラウザ：Chrome/Firefox
