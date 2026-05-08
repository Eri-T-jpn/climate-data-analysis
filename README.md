# 気象データ解析課題

環境情報論の演習にて、気象庁等の公開データを用いて統計解析を行ったプロジェクトです。

## 内容
- **分析1（主成分分析）**: `analysis_pca.html`
  - 国内6地点の気温偏差データから主成分分析（PCA）を用いて主要な変動パターンを抽出。
- **分析2（地図投影と可視化）**: `analysis_visualization.html`
  - Cartopyを用い、海面水温（SST）をモルワイデ図法や北極平射図法で可視化。
- **分析3（相関・回帰分析）**: `analysis_corr_regr.html`
  - 気候インデックスと各地の気象要素の相関・回帰係数を算出し、空間構造を解析。

## 使用技術
- Python (NumPy, Matplotlib, Cartopy)
- Jupyter Notebook
