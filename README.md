## ハマったところ

### 環境設定
* Node版のdanfo.jsはNodeのバージョン20以下でないと動かないライブラリが含まれている（執筆時点）。nvmなどでNodeのバージョンの切り替えが必要だった。
* nvmのイントールした後のnvmコマンドの利用には.zrcのターミナル環境設定が必要だった。
* danfo.jsのサンプルコードにrequire("danfojs-node")などの記述があるが、package.jsonでは"danfojs"であり、requireするときは"danfojs"と書かないとmodule not foundedとなる。
