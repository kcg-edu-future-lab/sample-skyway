# sample-skyway

SkyWayを使ってビデオ会議アプリケーションを作成するサンプルです。

まずはこのリポジトリをcloneしてください。
```
git clone https://github.com/kcg-edu-future-lab/sample-skyway
```

次に以下を参照し，無料アカウントを登録してAPIキーを取得してください。
https://webrtc.ecl.ntt.com/documents/javascript-sdk.html#_1-%E6%BA%96%E5%82%99

次に，key.js内に，APIキーを記述してください。

index.htmlがあるディレクトリでHTTPサーバを起動し，ブラウザで表示してください。

表示された画面の"接続する"ボタンを押すと，ビデオ会議に接続できます。カメラやマイクのチェックボックスを
onにすると，参加している他のブラウザに映像や音声が送信されます。


