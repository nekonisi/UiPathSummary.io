# Exception

## このページについて

- 例外処理について解説する。

## エラーメッセージの表示

- `Try Catch`で例外を補足できなかった場合、例外メッセージが表示される。
- UiPathではVB.NETを採用しているので、例外メッセージを調査する際は、VB.NET系の情報を探す。  
[参考](https://msdn.microsoft.com/ja-jp/library/system.exception.aspx)

## Try Catch アクティビティ

### 解説

- 例外処理の機能を実装する。

### アクティビティ図

![Try Catchアクティビティ](../img/Algorithm/TryCatchImg.png)

#### Try

- 監視するアクティビティを追加する。

#### Catches

- 監視する例外をコンボボックスから選択する。

#### Finally

- `Finally`句で実行するアクティビティを記述する。

### プロパティ

プロパティ名|説明
------------|----
DisplayName|表示名称

[TOPへ](../)
