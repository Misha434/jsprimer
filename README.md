# jsprimer

# 第一部: 基本文法
## 目次
- [JavaScriptとは](#anchor1)
- [コメント](#anchor2)
- [変数と宣言](#anchor3)
- [値の評価と表示](#anchor4)
- [データ型とリテラル](#anchor5)
- [演算子](#anchor6)
- [暗黙的な型変換](#anchor7)
- [関数と宣言](#anchor)
- [文と式](#anchor)
- [条件分岐](#anchor)
- [ループと反復処理](#anchor)
- [オブジェクト](#anchor)
- [プロトタイプオブジェクト](#anchor)
- [配列](#anchor)
- [文字列](#anchor)
- [文字列とUnicode](#anchor)
- [ラッパーオブジェクト](#anchor)
- [関数とスコープ](#anchor)
- [関数とthis](#anchor)
- [クラス](#anchor)
- [例外処理](#anchor)
- [非同期処理:コールバック/Promise/Async Function](#anchor)
- [Map/Set](#anchor)
- [JSON](#anchor)
- [Date](#anchor)
- [Math](#anchor)
- [ECMAScriptモジュール](#anchor)
- [ECMAScript](#anchor)
- [第一部: 終わりに](#anchor)

第二部: ユースケース
アプリケーション開発の準備
Ajax通信
エントリーポイント
HTTP通信
データを表示する
Promiseを活用する
Node.jsでCLIアプリ
Node.jsでHello World
コマンドライン引数を処理する
ファイルを読み込む
MarkdownをHTMLに変換する
ユニットテストを記述する
Todoアプリ
エントリーポイント
アプリの構成要素
Todoアイテムの追加を実装する
イベントとモデル
Todoアイテムの更新と削除を実装する
Todoアプリのリファクタリング

<a id="anchor1"></a>
<a href="#anchor1">
### JavaScriptとは
</a>

- JavaScriptとECMAScript:JavaScriptという言語はECMAScriptという仕様によって動作が決められています。
- JavaScriptは主にウェブブラウザの中で動くプログラミング言語
- JavaScriptを活用してアプリケーションのように操作できるウェブサイトをウェブアプリともいう
- Node.jsというサーバー側のアプリケーションを作る仕組みでも利用されている

#### JavaScriptの言語的な特徴
- 大文字と小文字を区別する
たとえば、次のようにnameという変数を大文字と小文字で書いた場合に、それぞれは別々のnameとNAMEという名前の変数として認識
```
// `name`という名前の変数を宣言
const name = "azu";
// `NAME`という名前の変数を宣言
const NAME = "AZU";
```

- 予約語を持つ
const など特別な言葉は予約語とも呼ばれます。 このキーワードと同じ名前の変数や関数は宣言できません。

  const, let など


- 文はセミコロンで区切られる
  JavaScriptは、文（Statement）ごとに処理していき、文はセミコロン（;）によって区切られます。 
  
  特殊なルールに基づき、セミコロンがない文も、行末に自動でセミコロンが挿入されるという仕組みも持っています。
  
  しかし、暗黙的なものへ頼ると意図しない挙動が発生するため、セミコロンは常に書くようにします .


- strict mode
  名前のとおり厳格な実行モードで、古く安全でない構文や機能が一部禁止されてるモード

  使用法
  ```
  "use strict";
  mistypedVariable = 42;
  ```


- 実行コンテキスト: ScriptとModule
JavaScriptの実行コンテキスト:"Script","Module"
  - "Script"
    多くの実行環境でデフォルトの実行コンテキスト。strict modeはデフォルトではない
  - "Module"
    JavaScriptをモジュールとして実行するために、ECMAScript 2015で導入された。strict modeはデフォルト 
- JavaScriptの仕様は毎年更新される


<a id="anchor2"></a>
<a href="#anchor2">
### コメント
</a>

```
// 一行コメントアウト

/* コメントアウト

/* 二行
コメントアウト
 */
```

<a id="anchor3"></a>
<a href="#anchor3">
### 変数と宣言
</a>

```

```

<a id="anchor4"></a>
<a href="#anchor4">
### 値の評価と表示
</a>
### データ型とリテラル
### 演算子
### 暗黙的な型変換
### 関数と宣言
### 文と式
### 条件分岐
### ループと反復処理
### オブジェクト
### プロトタイプオブジェクト
### 配列
### 文字列
### 文字列とUnicode
### ラッパーオブジェクト
### 関数とスコープ
### 関数とthis
### クラス
### 例外処理
### 非同期処理:コールバック/Promise/Async Function
### Map/Set
### JSON
### Date
### Math
### ECMAScriptモジュール
### ECMAScript
### 第一部: 終わりに

### 第二部: ユースケース
### アプリケーション開発の準備
### Ajax通信
### エントリーポイント
### HTTP通信
### データを表示する
### Promiseを活用する
### Node.jsでCLIアプリ
### Node.jsでHello World
### コマンドライン引数を処理する
### ファイルを読み込む
### MarkdownをHTMLに変換する
### ユニットテストを記述する
### Todoアプリ
### エントリーポイント
### アプリの構成要素
### Todoアイテムの追加を実装する
### イベントとモデル
### Todoアイテムの更新と削除を実装する
### Todoアプリのリファクタリング