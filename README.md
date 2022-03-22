[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/acorncat/unofficial-tools/blob/main/TokenizeForAIN.ipynb)

概要
==

[AIのべりすと](https://ai-novel.com)で使用されているトークナイザー([SentencePiece](https://github.com/google/sentencepiece)の学習済み単語分割モデル)で文章をトークンごとに分割します。

説明：
* 入力した文章のトークン数をカウントします。
* トークンに無い文字を抽出、強調します。

注意：
* 非公式ツールです。実際の仕様とは若干異なる可能性があります。
* Google Colabで実行しているため、入力文はGoogleのクラウドサーバーで処理されます。

◆【トークン数カウント】項目の説明
---

* sentence: 文章の入力欄です。ここに文章を入力して、実行ボタンを押してください。複数行入力したい場合はペーストしてください。※数万文字以上ペーストするとブラウザがフリーズする可能性があります。
* space: スペース・改行をこれに置換します。
* cut_mark: トークンを区切る文字です。
* check_unk: トークンに無い文字を強調します。AIには<unk>というトークンして認識されます。
* fontsize: 結果の文字サイズを変更します。※変更後、再度実行しないと反映されません。

ライセンス - License
---
下記のファイルを利用しています。  
spiece.model:  
Copyright 2021 Sta (https://huggingface.co/naclbit/gpt-j-japanese-6.8b)  
Lisensed under the Apache License, Version 2.0 (https://www.apache.org/licenses/LICENSE-2.0.txt)
