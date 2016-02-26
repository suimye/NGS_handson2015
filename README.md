#NGSハンズオン講習会
###ChIP-Seq解析基礎-森岡担当
###バイオインフォマティクス人材育成カリキュラム、次世代シークエンサ(NGS)ハンズオン講習会の講義資料、ならびに28年に行われた統合データベース講習会AJACSa三島2の講演資料です。

- [平成27年度NGSハンズオン講習会の公式HP](http://biosciencedbc.jp/human/human-resources/workshop/h27)
- [2015全日程の講義資料](http://www.iu.a.u-tokyo.ac.jp/~kadota/r_seq.html#bioinfo_ngs_sokushu_2015)
- [統合データベース講習会AJACSa三島2](http://dbcls.rois.ac.jp/archives/3094)

8/6以降も適宜更新作業を行っています。

ご質問などに関してはmsmorioka-tkyあっとumin.ac.jpまでお願いいたします。

- 2016.2: homerの使い方 update
- 2016.2: IGVの使い方 update


###参考資料
- [2014のChIP-seq解析、河岡先生の資料へのリンク](http://www.iu.a.u-tokyo.ac.jp/~kadota/bioinfo_ngs_sokushu_2014/20140911_4-4_kawaoka.pdf)
- [shellの使い方: 服部先生の資料へのリンク](http://www.iu.a.u-tokyo.ac.jp/~kadota/bioinfo_ngs_sokushu_2015/20150724_amelieff.pdf)
- [HOMER](http://homer.salk.edu/homer/index.html)
- [NGS Surfer's wiki ](https://cell-innovation.nig.ac.jp/wiki/tiki-index.php)
  -bowtie, bwaのmultimappingのときのリードの分散について[情報](http://tinyurl.com/ooeactg) 


####はじめに
本実習の達成目標は、“NGS解析の初心者がNGSデータの一つであるChIP-seqデータに触れ、ChIP-seq解析の流れを概要として掴み、自ら解析するときの足がかりとなる”ことを目指します。本実習で利用する方法は、一般的に利用される方法ではありますが、Biolinux8という限られた環境で行うという性質上、大変遺憾ながら最新の手法や、インストールの如何で個人差の生じるような方法をできるだけ利用しないような配慮がなされています。従って、あくまでも“練習”であり、自分で実際に臨むときは最新の手法やさらに良いソフトウェアを利用することをオススメします。

1. Linux操作については、門田先生、服部先生のLinux基礎の知識を前提にしています。Commandで分からないところがある場合は講義資料を参考にするようにつとめてください。
2. ソフトウェアの実行では、実習生のPC環境によって動作しない事があります。森岡が動作を保証するものではありません。ソフトウェアの動作については **ソフトウェアの開発者に聴くことが重要です。**
3. 遅れても焦らずに。まずは講師のデモ・レクチャーを聴いた後に時間を与えますので、その時に周りに聴いたり、先生方に聴いて進むようにしてください。



---



#NGS_handson2015
1. [初心者コース（森岡の講義とともに歩く）](https://github.com/suimye/NGS_handson2015/wiki/NGS_beginner)


  - ChIP-seqの基本原理と解析の流れ(pptで説明) 
  - [データの取得](https://github.com/suimye/NGS_handson2015/wiki/data_retrive)
  - [UCSC table browserからbedファイル作成](https://github.com/suimye/NGS_handson2015/wiki/repeat-region-from-UCSC_table_browser)
  - [データのQCと、ゲノムへのアライメント](https://github.com/suimye/NGS_handson2015/wiki/NGS_beginner)
  - [データの可視化(UCSC genome browser, IGV)](https://github.com/suimye/NGS_handson2015/wiki/ChIP-seq%E3%83%87%E3%83%BC%E3%82%BF%E3%81%AE%E5%8F%AF%E8%A6%96%E5%8C%96)
  - [Peak Callに基づくタンパク質-DNA結合領域の検出](https://github.com/suimye/NGS_handson2015/wiki/PeakCallAndMDA)

2. 中級者コース
  - Peak 領域の意味付けと統合解析(主にpptで説明)
      - [Ngsplotを使ったtagの分布解析](https://github.com/suimye/NGS_handson2015/wiki/NGSplotsOnBiolinux8)
      - [HOMERの統合解析](https://github.com/suimye/NGS_handson2015/wiki/Homer_Data_integration)
      - [NGSplotを使ったデータの統合](https://github.com/suimye/NGS_handson2015/wiki/Ngsplot_data_integration)


3. [中級者以上コース（一匹狼たちへの課題）](https://github.com/suimye/NGS_handson2015/wiki/NGS_senior)



 




