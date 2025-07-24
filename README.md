# JijZept Solver Benchmark Notebooks

JijZept Solver のベンチマークを実行する Jupyter ノートブックです。
QPLIB, MIPLIB のベンチマーク問題を使用して JijZept Solver のベンチマークを実行し、他のソルバーとの比較も行っています。

### 1. Notebook 起動方法

以下のバッジをクリックすることで、環境構築の手間なく Notebook を実行できます：

| Title             | Binder                                                                                                                                                      | Google Colab                                                                                                                                                                                      |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| benchmark_compare | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jij-Inc/JijZept-Solver-Benchmark-2025-07/main?filepath=benchmark_compare.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jij-Inc/JijZept-Solver-Benchmark-2025-07/blob/main/benchmark_compare.ipynb) |

- **Binder**: 必要なパッケージが自動インストールされているため、pip install 不要でそのまま実行可能です
- **Google Colab**: ノートブック中の`!pip install ~`のセルを手動で実行し、必要なパッケージをインストールしてください

### 2. JijZept Solver 無償 WebAPI 版 の利用申請

JijZept Solver 無償 WebAPI 版 を使用するには、事前に利用申請が必要です：

1. [利用申請フォーム](https://docs.google.com/forms/d/e/1FAIpQLScLTRxXGaN7egRkoYcq2ZvFoFXRyYInsmPXlyxk9pF11E9--g/viewform)から利用申請を行い、API アクセスに必要なトークン等を入手する
2. ノートブック内の説明を参考に、API アクセスに必要なトークン等をノートブック内で設定する
