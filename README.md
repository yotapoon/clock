# clock
粉体時計に関するシミュレーションを行いアニメーションと粒子の偏りの時間変化のグラフを生成する。

### 使い方
"gcc -o gif gif.c"でコンパイル、"gif"で実行するだけ。
gif.cがsetting.txtを生成し、また"gnuplot gif.txt"を実行させることによりアニメーションが生成される。
たいていのパラメータの情報はsetting.txtに入れられるので自動で修正されるが、粒子の大きさやその比率はplot.txtで手作業で変更するしかない。

