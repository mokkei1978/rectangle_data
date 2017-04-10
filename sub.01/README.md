SUBオンライン・ネスティング入力ファイル (sub.01)
========

MRI.COMのオンライン・ネスティングに必要な入力ファイル。


ファイル
--------

prep/nest/topo/ で作成。

  * nest.d       作業用の中間ファイル   (sub/make_grid.sh)
  * upscale.gd   フィードバック領域     (sub/make_upscale_zone.sh)
  * downscale.gd 親モデル結果を子モデルで保持する領域 (sub/make_downscale_zone.sh)

prep/nest/remap/ で作成。

  * rmp_c2pt_3d.d                 (sub/make_remap_sub2par.sh)
