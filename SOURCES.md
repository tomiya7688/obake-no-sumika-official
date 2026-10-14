# 資料の出典・位置付け・更新方法

このリポジトリは、単なるリンク集ではなく、**設定本文と読み物を実際に収録する公式案内所**です。情報ごとに、どこから来たかと確定度合いが違います。

## 1. 掲載した公式設定本文

2026年10月15日に次の文書から**設定本文を取り込んで掲載**しました。

| このリポジトリの文書 | 掲載元 | 内容 |
| --- | --- | --- |
| [setting/WORLD.md](setting/WORLD.md) | [chatgpt-obakenosumika / WORLD.md](https://github.com/tomiya7688/chatgpt-obakenosumika/blob/main/WORLD.md) | 住処、生活、外出、帰り道、食べ物、能力など |
| [setting/CHARACTERS.md](setting/CHARACTERS.md) | [chatgpt-obakenosumika / CHARACTERS.md](https://github.com/tomiya7688/chatgpt-obakenosumika/blob/main/CHARACTERS.md) | まる、かどか、ふたりの関係、口調など |

取り込み時のGit blob SHA：

- WORLD.md: `5d8058fed5d42800805566cb345009ffc74bc8fb`
- CHARACTERS.md: `e505cc849a76e99843d52b38effdea99c54ed210`

キャラクター画像の相対パスのみ、こちらからも画像が表示されるように配信元URLへ変更しました。本文の設定は省略していません。取り込みの案内文は各ファイル末尾に加えています。

**世界・キャラクター設定の管理上の正本は、引き続き掲載元のmainブランチです。** この案内所は全文掲載版なので、更新が遅れた場合は設定に差が生じることがあります。

## 2. 作者の制作メモから採用した内容

個人用の外部メモリ（my-memory）の「作品/おばけの住処/README.md」から、作品に関係する範囲だけを抽出しています。

- [stories/README.md](stories/README.md)：賭け場、飴の罠、いなくなったりんご、白いみかんと折れたナイフの**小話メモ全文**を収録。
- [setting/NOTES.md](setting/NOTES.md)：過去の白いおばけに関する描写、ぬいぐるみの造形指定と正式設定の違い、確定／未確定の整理を掲載。

元のメモリリポジトリは個人用であり、作品以外の情報は公開しません。小話はそのまま新しい公式設定だと断定せず、「創作メモ」として分類しています。

## 3. 作品案内と利用条件

- [PROJECTS.md](PROJECTS.md)：各リポジトリのREADME、ゲーム仕様書、2026年10月12日付の制作者の開発メモに基づいて内容を紹介。
- [LICENSE_GUIDE.md](LICENSE_GUIDE.md)：[Obake Character License v1.2](https://github.com/tomiya7688/Obake_Lisense/blob/main/LICENSE.md) を説明するための要約。法的な正本の代替ではありません。

## 4. 更新するときのルール

1. 世界設定の変更は、元の WORLD.md / CHARACTERS.md の最新の内容を確認する。
2. 掲載版にも**本文を更新**する。リンクだけを貼り直す運用にはしない。
3. メモから新しい話を追加するときは、確定設定か創作案かを書き分ける。
4. ゲーム固有の仕様を、おばけの普遍的な能力・性質へ勝手に置き換えない。
5. ライセンスの版・内容が変わった場合は、日本語正本で改めて確認する。

こうして、読む場所としての「公式」と、正しい出典管理の両方を保ちます。
