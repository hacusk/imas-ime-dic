hacusk/imas-ime-dic
=====================
forked from [maruamyu/imas-ime-dic](https://github.com/maruamyu/imas-ime-dic)

[THE IDOLM@STER (アイドルマスター)](http://idolmaster.jp/)にかかわる単語を記述した日本語IME向けの辞書ファイルです。

[アイマスDB](https://imas-db.jp/)様が公開/管理している辞書ファイルをmacOSに最適化したものになります。

アイマスDB様より先行して辞書の追加を行う場合があります。
後々にアイマスDB様が追加した際に、こちらで先行して追加していたものとで違いが発生した際にはアイマスDB様の方にあわせます。

## ファイル説明

- dic.txt
	- アイマスDB様が公開しているオリジナルのものになります。こちらはmacOSの日本語IMEに当てることはできません。
- dic_jim.txt
	- アイマスDB様が公開しているものにmacOS向けのアレンジを加えたものになります。
	- システム環境設定の入力ソースの追加辞書の設定で、このファイルをドラッグ&ドロップすると登録できます。
	- 追加辞書での登録の場合、使用上iOS端末とは辞書が同期されませんのでご注意ください。
- dic.plist
	- アイマスDB様が公開しているものをベースに、ユーザー辞書として登録できるようにしたものになります。
	- システム環境設定のユーザー辞書の項目で、このファイルをドラッグ&ドロップすると登録されます。
	- 使用上、品詞の設定ができないため品詞を意識したい場合は、dic_jim.txtの追加辞書の方をお使いください。

## 想定環境

- macOS
	- Japanese Input Method(旧:ことえり)
	- テキストエディタで編集可能
- iOS
	- 標準日本語IME
	- macOSにてdic.plistを用いて登録した場合のみ、使うことができます。
- 以下の文字が利用可能
	- 﨑 … 「赤﨑千夏」など
	- ♥ … 「私はアイドル♥」など
	- ♡ … 「仲良しでいようね♡」など
	- Ø … 「ØωØver!!」
	- ➚ … 「JOKER➚オールマイティ」
	- è … 「Cafè Parade」
	- 俠 … 「俠気乱舞」
	- ✿ … 「花ざかりWeekend✿」

## 取り決め

アイマスDB様の取り決めに基づき、以下の通りにします。但し、dic.plistはこれには準じません。

- 文字コードは UTF-16 LE
- 改行コードは CRLF

## License

リポジトリ内のテキストファイルは、MITライセンス下で配布されます。

This repository is released under the MIT License, see [LICENSE](LICENSE)

各社の商標または登録商標が含まれる場合がありますが、営利利用を意図したものではありません。

## コントリビューション

歓迎します。
forkして、新規branchを作成して、pullリクエストしてください。
