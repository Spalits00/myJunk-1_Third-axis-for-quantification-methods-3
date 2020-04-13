# myJunk#1 [数量化Ⅲ類における３次元空間の実現]
このプロジェクトは，Spalits00によるmyJunkプロジェクト１作目です．
このmyJunkプロジェクトでは，いま世の中で広く使われている「数量化III類」というグラフ（のようなもの）に軸を追加したときの有用性や使用感について検証・実験していきます．
拙い制作ですがよろしくお願いします．
※僕はこの数量化理論について特に知識があるわけでもないので，数学的な部分についてはそこまで追求しません．僕が作りたいのは学生同士の話し合いなどで使われるグラフであり，その中身については全く考慮しないつもりです．
## ここで言う数量化Ⅲ類についての説明
異なる性格の２つの軸を用意し，その２軸が作る２次元空間にデータを点として視覚化するという一種のグラフ（散布図）作成における手法（ではないのですがここではそういうていで話を進めていきます）です．
この手法の良い点は「クロス表よりも点（データ）同士の関係が分かりやすくなる」という点で，この手法は主に点同士の「類似性」を調べるために用いられます．
僕は主にこのページを参照しながら作っていくつもりです：http://www2.tbb.t-com.ne.jp/ohara/tahenryou/Suryou3.htm
## 実際に何を作る？
Unityというゲームエンジンを用い，プログラム内で作成した３次元空間を２次元空間（ディスプレイ）に投写するという方法で作っていきます．３次元空間を作成・運用し，２次元空間に現像するという手間を省くためです．
具体的には，まずゲームエンジン内で２次元と３次元両方のグラフで同じ（２つの値を持つ）データを表現し，３次元グラフの点には３つ目の値を設定します．また，同時に１つ目と３つ目，２つ目と３つ目を表現する２次元グラフも作成します．
次に，３次元グラフでの最低限の操作性を確保するために，３次元グラフには，人の思い通りに原点を中心として回転する機能を追加します．（ここまでで１〜２ヶ月を想定）
その後に，数名の知人に協力してもらいながら，３次元グラフでの操作性を改善していきます．
最終的には，２次元グラフと３次元グラフそれぞれの利点と残った改善点，それから欠点について検証し，この実験（制作）を終わります．

