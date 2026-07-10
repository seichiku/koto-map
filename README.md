# 江東区 整骨院・鍼灸院 出店エリア分析マップ

町丁目別人口（住民基本台帳 2026-07-01）× Googleビジネス掲載の整骨・接骨・鍼灸院143件の需給ヒートマップ。

- `index.html` — 分析ダッシュボード（SVG・指標切替・ランキング・人口内訳）
- `streets.html` — 街路地図版（Leaflet + OpenStreetMap）

データ更新時は元セッションの `koto-research` 一式（人口CSV集計→競合収集→analyze.py→テンプレートに埋込み）を再実行。
