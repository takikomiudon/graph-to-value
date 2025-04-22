# グラフ画像から数値データを抽出するプロジェクト

このプロジェクトは、OpenAI の Vision モデルを活用して、様々な形式のグラフ画像から元の数値データを推測・抽出するシステムを提供します。

## 特徴

- 様々なグラフタイプに対応（折れ線グラフ、棒グラフ、散布図、円グラフなど）
- OpenAI GPT-4o モデルによる高精度なデータ抽出
- 抽出したデータを使用したグラフの再現機能
- 結果を CSV や JSON でエクスポート可能

## セットアップ方法

### 必要条件

- Python 3.11
- Anaconda/Miniconda
- Poetry
- OpenAI API キー

### インストール手順

1. Conda で環境を作成する:

```bash
conda create -n graph-to-value python=3.11 -y
conda activate graph-to-value
```

2. Poetry でパッケージをインストールする:

```bash
poetry install --no-root
```

3. OpenAI API キーを設定する:

```bash
export OPENAI_API_KEY="your-api-key-here"
```

## 使用方法

1. Jupyter Notebook を起動する:

```bash
jupyter notebook
```

2. `graph_to_value.ipynb` ファイルを開いて実行する

## 使用例

- テスト用のグラフを生成して解析
- 独自のグラフ画像をアップロードして解析
- 抽出したデータを CSV/JSON でエクスポート

## ライセンス

MIT ライセンス
