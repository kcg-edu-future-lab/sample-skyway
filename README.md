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

表示された画面の"接続する"ボタンを押すと，ビデオ会議に接続できます。カメラやマイクのチェックボックスを
onにすると，参加している他のブラウザに映像や音声が送信されます。


