FashionScalaNovel
=================
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/Kuchitama/FashionScalaNovel?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
ファッションScala小説

主人公：コザケ シンイチ

これは、孤高のプログラマコザケの一夜の物語。雰囲気でScalaを書き始めた彼を待ち受けるのは、まさに孤独との戦いであった。

今日もシンイチは行きつけの輸入ビールも飲めるカジュアルイタリアンSCALAに入る。

シンイチ「マスター、いつもの」

糖質制限中のシンイチはハイボールを注文する。

彼の、長い夜が始まった。

# 一章 sbt との邂逅

「おい、お前 sbt って知ってるか？」

このところ、この店でよく見かけていた男が突然話しかけてきた。

「ん、一体それは何だ？」

「おいおい、sbt も知らねぇとは話にならねぇぜ・・お前、そんな調子でこれから先大丈夫か？いっぱしの Scala プログラマなら、みんな sbt 使ってコンパイルしてるんだぜ。」

「オレはいくつものミッションクリティカルなエンタープライズシステムを Java で構築してきた。そいつらをプロダクション環境に送り出してきた Maven は戦友だよ。あの XML が実に手になじむ。だから Scala でも Maven でコンパイルしているし、それで何も問題がないね。」

「最初はみんなそう言うんだ。でも、この辺じゃみんな sbt 使ってる。きっとお前もそうなるよ。また会おう。」

そう言って男は立ち去っていった。男のシャツには達筆な毛筆で scalaz と書かれていた。

***

最後にバーボンを一杯煽ったオレは店を出た。もちろんバーボンの糖質は0だ。

家に着いて妻と子どもの寝顔を確認すると、一人リビングでMacBookを開く。店で出会ったあの男の去り際の言葉が忘れられなかった。

「sbt...」

検索結果を確認する。一番上の検索結果は英語だった。オレは何を考える事もなく、いつも通り日本語のページで一番上位に出ているリンクを開く。

「始めるsbt...強力なビルド定義 (build definition) を作ることができる...ほう」

開いたページはsbtの入門ドキュメントの和訳だった。そこの記述をみるとどうやらビルドに関連したツールらしい。そういえば、店で出会ったあのscalazシャツの男も、sbtを使ってScalaをコンパイルすると言っていた。

オレは、sbtのページのホームへのリンクを叩く。表示されたのは英語だった。
そこには、

    The interactive build tool
    Use Scala to define your tasks. Then run them in parallel from the shell.

と書かれていた。やはり、sbtはScalaのビルドツールのようだ。それだけ確認したオレは先ほどの和訳のページに戻った。
