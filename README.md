# kadai5
# HTTPにまつわる用語
## HTTPとは
- WebサーバとWebブラウザ間の[プロトコル](https://wa3.i-3-i.info/word11.html)
  
## URLとは
- インターネット上の情報の場所

## HTTPリクエストとは

<img width="130" alt="HTTPリクエスト" src="https://github.com/tomoya0844/kadai5/assets/146510558/2c139cae-43f4-4e53-82d3-5c98cf1a799d.png">

| 名称 | 意味 |
| :-: | :-: |
| HTTPリクエストライン | 「HTTPリクエストの部品で『何を、どうしたい』が書かれている場所 |
| HTTPリクエストヘッダー | お願いごとやお願い元に関するあれこれ』が書かれている場所 |
| HTTPリクエストメッセージボディ | 「HTTPリクエストの部品で、補足のメモ書きが書いてある場所 |


## パス変数とは
```java:main
http://example.com/user/1
```
↑ここで言う**１**のこと
- 詳しくは[こちら](https://zenn.dev/fujishiro/scraps/3a060b10b17a93)

## クエリ文字列とは
- 特定のものに条件を追加する際に必要なものなのか
```java:main
https://zenn.dev/search?q=Laravel
```
↑ここで言う**search**がパスパラメータで、**?q=Laravel**がクエリパラメーターにあたる
- 詳しくは[こちら](https://online.dhw.co.jp/kuritama/query-string/#:~:text=%E3%82%AF%E3%82%A8%E3%83%AA%E6%96%87%E5%AD%97%E5%88%97%EF%BC%88URL%E3%83%91%E3%83%A9%E3%83%A1%E3%83%BC%E3%82%BF%E3%83%BC%EF%BC%89%E3%81%A8%E3%81%AF%E3%80%81%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E3%81%AB,%E3%81%A4%E3%81%91%E5%8A%A0%E3%81%88%E3%82%8B%E3%81%93%E3%81%A8%E3%81%8C%E5%8F%AF%E8%83%BD%E3%81%A7%E3%81%99%E3%80%82)

## HTTPメソッドとは
| HTTPメソッド | はたらき |
| :-: | :-: |
| GET | 	リソース情報を取得する |
| POST | 新しいリソース情報を送り込む |
| PUT | 	リソース情報を新しい情報で置き換える |
| PATCH | リソース情報の一部を新しい情報で書き換える |
| DELETE | 	リソース情報を削除する |

## HTTPステータスコードとは
- HTTPリクエストの結果を表す3桁の数字

| HTTPステータスコード | 意味 |
| :-: | :-: |
| 200 | リクエストが成功したことを示します。成功が意味することは、 HTTP メソッドにより異なります |
| 201 | リクエストは成功し、その結果新たなリソースが作成されたことを示します |
| 400 | 構文が無効であるためサーバーがリクエストを理解できないことを示します |
| 404 | サーバーがリクエストされたリソースを発見できないことを示します |
| 500 | サーバー側で処理方法がわからない事態が発生したことを示します |

- 更に詳しくは[こちら](https://developer.mozilla.org/ja/docs/Web/HTTP/Status)

## HTTPレスポンスとは

<img width="130" alt="HTTPレスポンス" src="https://github.com/tomoya0844/kadai5/assets/146510558/ac440a4e-de70-45fd-ab41-409e86699079.png">


| 名称 | 意味 |
|:-: | :-: |
| HTTPステータスライン | 「HTTPレスポンスの部品で『HTTPリクエストの結果』が書かれている場所 |
| HTTPレスポンスヘッダー |『ステータスラインに書ききれないレスポンスの情報』が書かれている場所 |
| HTTPレスポンスボディ | 『相手が欲しがってたファイルの中身』が書いてある場所 |

## JSONとは
> JSONとは、
> JavaScript Object Notation（ジャヴァスクリプト・オブジェクト・ノーテーション）の略

- JavaScriptと相性が良い、ファイルの書き方ルール

| 単語 | 意味 |
| :-: | :-: |
| JavaScript | [プログラミング言語](https://wa3.i-3-i.info/word1897.html)の[「JavaScript」](https://wa3.i-3-i.info/word11438.html) |
| Object | 	[オブジェクト](https://wa3.i-3-i.info/word1119.html)。「対象」とか「物」とか |
| Notation | 	[「表記法」](https://kotobank.jp/word/%E8%A1%A8%E8%A8%98%E6%B3%95-613173)とか |

 ↓記載例↓
  ```json
[
  {
    "ID": 1,
    "Name": "Taro",
    "Age": 16
  },
  {
    "ID": 2,
    "Name": "Hanako",
    "Age": 78
  },
  {
    "ID": 3,
    "Name": "Yuji",
    "Age": 54
  }
]
 ```
