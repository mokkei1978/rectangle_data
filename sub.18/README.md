SUBモデル設定ファイル ver.18
========

双方向オンライン・ネスティング(U点接続)のための設定ファイル。


ファイル
--------

()内は作業したツール, ディレクトリ

  * buffer_... (prep/nest/topo/make_weight.sh)
  * hdts/uv_sub_3d.d (prep/nest/topo/make_sponge_sub.sh)
  * hvisc_add_sub_t.d (prep/nest/topo/make_viscadd_sub.sh)
  * rmp_tw_p2c... (prep/nest/remap/make_remap_par2sub.sh)
  * rmp_c2p... (prep/nest/remap/make_remap_sub2par_areaave.sh)
  * rmp_c2p..., rmp_tw_c2p[xy]...
               (prep/nest/remap/make_remap_sub2par_pinpoint.sh)


サブディレクトリ
--------

  * grads/ grads用ファイル
  * fail/  mk_side_flx_c2p_v2.F90 のバグ修正を直す前の変換テーブル
