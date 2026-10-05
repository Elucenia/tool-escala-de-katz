<!-- ELUCENIA technical documentation · escala-de-katz · ja · no clinical/professional/rights approval -->

# Katz指数（基本的日常生活動作）

[条件・出典・許諾](https://elucenia.org/ja/tools/escala-de-katz)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 入浴（自立：一人で入浴、または身体の一部のみ介助）

`banho`

- `0` — 介助が必要
- `1` — 自立

### 更衣（自立：服を取り、靴ひも以外は介助なく着衣）

`vestir`

- `0` — 介助が必要
- `1` — 自立

### 排泄（自立：トイレ移動、清潔、衣服の調整を介助なく行う）

`higiene`

- `0` — 介助が必要
- `1` — 自立

### 移乗（自立：介助なくベッド・椅子に横たわる、起き上がる）

`transf`

- `0` — 介助が必要
- `1` — 自立

### 禁制（自立：尿便を完全に管理）

`contin`

- `0` — 介助が必要
- `1` — 自立

### 食事（自立：皿から口へ介助なく食べ物を運ぶ）

`alim`

- `0` — 介助が必要
- `1` — 自立

## 方法の版

二値式Katz ADL：6活動、合計0–6；Katzら1970を一部改変したHIGN 2019様式；1963のA–G分類は含まない

## 記載された計算式

他者の監督・指導・介助なく自立した動作ごと1点：入浴、更衣、トイレ、移乗、排泄自制、食事。計0–6。

## 限界・対象集団

指数の版と、各活動での自立の定義を記録してください。2008年のブラジルの適応版は、文化的な同等性と信頼性を研究しましたが、この二値の実装や新しい翻訳を認証するものではありません。ローカルの0–6の合計は、歴史的なA–G分類ではありません。 6活動の二値合計は、Katzら1970を一部改変したと記載するHIGN 2019様式に照らして確認した。この資料は1963のA–G分類ではなく、2008年ブラジル版や現在の独自翻訳を認証するものではない。自立の例外と高齢者の基本的日常活動を評価する目的は、対応する様式に従う必要がある。

## 参考文献

- [Katz S et al. Studies of illness in the aged. The index of ADL: a standardized measure of biological and psychosocial function. JAMA, 1963.](https://doi.org/10.1001/jama.1963.03060120024016)

- [Lino VTS et al. Adaptação transcultural da Escala de Independência em Atividades da Vida Diária (Escala de Katz). Cad Saude Publica, 2008.](https://doi.org/10.1590/S0102-311X2008000100010)

- [McCabe D. Katz Index of Independence in Activities of Daily Living. HIGN/NYU, Issue 2, revised 2019; slightly adapted from Katz et al. 1970.](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_2.pdf)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
