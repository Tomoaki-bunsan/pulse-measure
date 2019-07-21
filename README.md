# pulse-measure
- パソコンのカメラから映像を1フレーム毎に読み込み、その画像の平均の輝度値(R)を計測してグラフに出力するプログラム．
- jupyter notebook での使用を前提としている．

- 使用したライブラリ
  - openCV
  - mutplotlib
  - numpy

-使い方
  - 実行前にカメラに指を当てておく
  - 実行するとしばらくカメラが稼働する
  - 200個データをとるとカメラが止まり、グラフが作られる
  - カメラの画像が灰色の画面しか映さないときがあるが、実際は数値は取れているので特に問題ない．
  
- 参考にしたサイト
  - https://ensekitt.hatenablog.com/entry/2017/12/19/200000     カメラから1フレーム毎に画像を取得する方法
  - https://postd.cc/image-processing-101     画像の平均の輝度の求め方(演習の部分)
- gifファイルを作るのに時間がかかりすぎるので、mp4ファイルで代用
![result](https://github.com/TomcaT1229/pulse-measure/edit/master/MOV=0255.mp4)
