# これは何？

メッセージを表示するSAORIです。
内部的にはMessageBoxを呼び出しているだけ。

# 使い方

Argument0: ゴーストのhwnd
Argument1: メッセージの内容
Argument2: ウィンドウのタイトル
Argument3: フラグ(int)

Result: MessageBoxの戻り値に同じ

詳しくは
https://learn.microsoft.com/ja-jp/windows/win32/api/winuser/nf-winuser-messagebox
のパラメーターを参照のこと。

Argument3は正しく指定しないとうまく動かなかったりエラーになったりするかも。

偶然にも安馬さんのものと丸かぶりした。
https://ambergonslibrary.com/ukagaka/9132/

