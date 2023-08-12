# ctrl-alt-ime-ahk

> **Note**
> このリポジトリは[alt-ime-ahk](https://github.com/karakaram/alt-ime-ahk)のフォークです。

## 概要

`Ctrl`キー + `Alt`キーの同時押下でIMEモードのON/OFFを切り替えるスクリプトです。
* `Ctrl + 左Alt`キーの押下で`IME OFF`に切り替え
* `Ctrl + 右Alt`キー押下で`IME ON`に切り替え

## 動作環境

* Windows11

## ご利用にあたって
1. 本リポジトリをダウンロードし、`ctrl-alt-ime-ahk.ahk`をAutoHotKeyでコンパイルしてください。
2. コンパイルが成功するとexeファイルが生成されます。適当なフォルダに移動して頂いても構いません。
3. exeファイルをダブルクリックするとプログラムが起動し、タスクトレイに「H」アイコンが現れます。  
4. 本プログラムを終了させる際はタスクトレイアイコンを右クリックし、「Exit」をクリックしてください。
5. アンインストールは手順1～2で生成したexeファイルを削除するだけです。


### 自動起動させる場合
1. エクスプローラのアドレスバーに `shell:startup` と入力し、Enterを押ください。「スタートアップ」という名前のフォルダに移動されるはずです。
2. 「ご利用にあたって」の手順1～2で生成したexeファイルへのショートカットを、「スタートアップ」フォルダに作成してください。
    ※アンインストール時にこちらのショートカットを削除するのをお忘れなく。

## JetBrains 製の IDE で使う場合は Tool Buttons をオンに  

> **Warning**
> 本章はフォーク元である`alt-ime-ahk`のREADMEを抜粋したものですが、本スクリプト(`ctrl-alt-ime-ahk`)では未検証です。JetBrains社製品との組み合わせで異常終了する場合はお試しください。  

IntelliJ IDEA など JetBrains 製の IDE をお使いの方は「上部メニューバー　＞　View　＞　Tool Buttons」をオンにしてください。  

オフのまま使うと Alt キーを離した際に alt-ime-ahk.exe がエラー終了します。
