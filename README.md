# sample-skyway

SkyWayを使ってビデオ会議アプリケーションを作成するサンプルです。

まずはこのリポジトリをcloneしてください。
```
git clone https://github.com/kcg-edu-future-lab/sample-skyway
```

次に以下を参照し，無料アカウントを登録してAPIキーを取得してください。
https://webrtc.ecl.ntt.com/documents/javascript-sdk.html#_1-%E6%BA%96%E5%82%99

APIキーの利用可能ドメイン名に，localhostを追加してください。

次に，key.js内に，APIキーを記述してください。

htmlファイルがあるディレクトリでHTTPサーバを起動し，ブラウザで表示してください。例えばpython3がインストールされていれば，以下のコマンドでサーバを起動できます。
```
python3 -m http.server
```

このサンプルは4つのステップで作成されています。それぞれ次のような機能を実装しています。

1. [01_getUserMediaAndPlay.html](https://github.com/kcg-edu-future-lab/sample-skyway/blob/main/01_getUserMediaAndPlay.html) - 自分のPCのカメラ映像をマイク入力を再生するだけのサンプル
2. [02_logAndConnectToSkyWay.html](https://github.com/kcg-edu-future-lab/sample-skyway/blob/main/02_logAndConnectToSkyWay.html) - SkyWayに接続するサンプル。このサンプル以降，key.jsにSkyWayのキーを設定しておく必要があります。
3. [03_connectMedia.html](https://github.com/kcg-edu-future-lab/sample-skyway/blob/main/03_connectMedia.html) - 他の利用者の音声/映像を接続しビデオ会議を実現するサンプル。
4. [04_virtualBackground.html](https://github.com/kcg-edu-future-lab/sample-skyway/blob/main/04_virtualBackground.html) - 仮想背景を実現するサンプル。

3,4で表示された画面の"接続する"ボタンを押すと，ビデオ会議に接続できます。カメラやマイクのチェックボックスをonにすると，参加している他のブラウザに映像や音声が送信されます。

