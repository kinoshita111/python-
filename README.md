# python-
ここではPythonを利用して作成したものたちを紹介する

ipynb ファイルは，Google Colaboratory 上での動作を想定している．

・
OpenNNT ipynb

・
画像分類器 ipynb

・
物体認識器 ipynb

・
動作認識器 ipynb



OpenNNT ipynb

ここではOpenNNTを実装している。

日英対訳コーパスである「京都関連文書対訳コーパス」
を利用しており，学習時間を短縮するために文長を制限することが課題だった 。

実装の際には，文長を10以下に制限することで， 学習時間を短縮させている．学習にはディープラーニングモデルである，Enco derDecoderの中のTransformerと呼ばれるモデルを利用して行っている． 

画像分類器　ipynb

plane，car，bird，cat，deer，dog，frog，horse，ship，truck　というクラスがあり，画像をどれかに分類するようになっている．  CNNは入力層，畳み込み層，プーリング層，畳み込み層，全結合層，全結合層，全結合層，出力層の順に構成している．  訓練データやテストデータはランダムに入手するようになっている．  結果では，予測精度は53％だった．






