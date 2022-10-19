オフライン・ネスティング子モデル用の側面境界ファイル v1 (offnestsub.01)
========

OFFNESTSUB の単体テストで用いる入力ファイル。
sub.11 から real(4) に変更。


データ内容
--------

側面境界ファイル。

  * off_barotropic_[ens] - 東、北、南の順圧モデル変数
  * off_tracer_[ens] -  東、北、南の水温塩分
  * off_uv_[ens] -  東、北、南の流速
  * off_lidx
  * off_pgrd

統合テスト nest_off の設定で作成した。
1月11日0:00から1月21日0:00まで、30分毎の241レコード。real(4)


作成
--------

  * 坂本, 2022/10/19
  * rectangle nest_off
  * #6332 MRI.COM 単体テスト offnestsub の境界値を単精度に変更する
