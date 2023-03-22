# README

## 変数の命名で気をつけたこと
何の機能を持つメソッドかわかりやすくするよう心がけた

## こだわりのポイント
- 投入されたお金を金額だけでなく、枚数でも記憶できるようにした

## 質問事項
- ローカル変数名が冗長になり可読性を下げている気がします（42行目のavailble_drinks_strなど）
  もっとよい命名基準はございませんでしょうか。

- コードのbuyメソッドのネストが不必要に深くなり可読性を下げているのではないかと感じています。
  ネストを浅くして可読性を向上させる方法をご教示ください。
  - 上記に関連して、開発において1つのメソッドの定義において何階層くらいまででネストは許容されるのでしょうか。

- 1つのメソッドが持つ機能が増えすぎた場合にメソッドを分けることがあると思いますが、その際に注意すべきことをご教示ください。

- buyメソッド/slot_moneyメソッドに機能を盛り込みすぎている気がしています。
  - 上記のメソッドをいくつかの機能に分割するとすれば、どのようにされるのかご教示ください。

- メソッドを定義する際、どのくらいの単位(機能)で1つのメソッドとするのか目安・基準をご教示ください。

- プログラミングの仕事及び学習にChatGPTを有効活用する方法と、注意点についてご教示ください。
  - プロンプトを工夫すれば欲している機能を叶えるコードを記述してくれると思うのですが、その精度を高めるため
    にすべきプロンプトの記述法
  - ChatGPTによってコードを記述させ、かつそれを解説させて学習するという学習方法の利点・不利点をご教示ください。

- 今回のコード全体をリファクタした場合、どのようになるでしょうか。
  - 上記に関連して、コードのリファクタ前のコードの欠点、改善のために学ぶべきこと（心掛けるべきこと）をご教示ください

- コードを書く際、可読性を上げるために重視していることは何ですか？
  - 上記の実現のために使用するメソッドやクラスの定義のひな形・社内ルールのようなものはありますか？

- コードを書く際、処理速度を遅くしないために重視していることは何ですか？
  - 上記の実現のために使用するメソッドやクラスの定義のひな形・社内ルールのようなものはありますか？
