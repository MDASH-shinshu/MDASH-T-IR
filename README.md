# 画像認識へのAI適用（工学部）

信州大学「画像認識へのAI適用（工学部）」 教材リポジトリ

## 教材形式

* Google colab版: 直接colab環境で実行できる形式（変更したければ個々人のGoogleドライブへコピーが必要）
* HTML版: Jupyter Notebook版からのHTMLエクスポート (HTML)
* PDF版: Jupyter Notebook版からのPDFエクスポート (PDF)
* Reveal.js版: Jupyter Notebook版（Slide指定あり）からのReveal.js slides版をエクスポート (HTML)

## GitHubからeALPSへのデプロイ方法

1. 基本的に，Google colab版をmasterとしてから，Jupyter Notebook版としてコピー後 調整する． (.ipynb)
2. Jupyter Notebook : HTML版をエクスポートする． (.html)
3. Jupyter Notebook : 印刷プレビュー経由でPDF保存する．(.pdf)
4. Jupyter Notebook : Slide指定でRISEの動作を確認後， Reveal.js slides版をエクスポートする． (.slides.html) <https://revealjs.com/>

## 目次

* 概説
* [A] 3層型ニューラルネットワークによる学習と識別
* 適用事例(A1) 文字認識における曲線の屈曲度の判定ファイル
* 適用事例(A2) 楽譜の音符検出における記号判定ファイル
* 適用事例(A3)、プログラミング演習(E1) 3層型ニューラルネットワークを用いた数字認識
* [B] 畳み込みニューラルネットワークによる学習とクラス分類
* 適用事例(B1)、プログラミング演習(E2) 畳み込みニューラルネットワークを用いた数字画像認識
* 適用事例(B2)、プログラミング演習(E3) 畳み込みニューラルネットワークを用いたカラー画像認識
* 参考文献

# memo

2025.2.26 URL変更された (common, otherサーバ)

## 数理DS コア3科目（年度更新されない版） URL

* DS基礎 <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=87>
* DE基礎 <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=88>

* 新DS・DE基礎(構築中) <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=86>
* 新AI基礎 <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=89>

## 工学部 学部共通科目 データサイエンス科目（2023 R5年度版）　URL

* DS基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=413>
* DE基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=414>
* AI基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=415>

## 工学部 学部共通科目 データサイエンス科目（2024 R6年度版）　URL

* DS基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=594>
* DE基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=401>
* AI基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=595>

## 学外連携・その他 eALPS URL

### 経産省 共同研究講座

* 産学連携 / デジタル人材育成共同研究講座
<https://lms.ealps.shinshu-u.ac.jp/other/course/index.php?categoryid=15>

* データサイエンス(DS)概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=26>
* データエンジニアリング概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=27>
* 機械学習概論I
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=28>
* AIエンジニアリング概論（佐藤真平先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=29>

### 工学教育寄附講座

* 産学連携 / 工学教育寄附講座
<https://lms.ealps.shinshu-u.ac.jp/other/course/index.php?categoryid=16>

* データサイエンス概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=30>
* データエンジニアリング概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=31>
* データマイニングと機械学習概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=79>
* 画像認識へのAIの適用（宮尾先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=33>
* AI技術による自然言語処理ツール入門（小形先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=32>
* 基礎制御設計（千田先生）
<https://lms.ealps.shinshu-u.ac.jp/other/enrol/index.php?id=35>


# jupyter notebook viewer

* sec.3のノートブックを直接表示する例
https://nbviewer.org/github/MDASH-shinshu/MDASH-T-DS/blob/main/3/3_data_search_and_visualization_colab.ipynb
