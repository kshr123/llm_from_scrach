# つくりながら学ぶ！LLM 自作入門

https://www.amazon.co.jp/%E3%81%A4%E3%81%8F%E3%82%8A%E3%81%AA%E3%81%8C%E3%82%89%E5%AD%A6%E3%81%B6%EF%BC%81LLM-Compass-Books%E3%82%B7%E3%83%AA%E3%83%BC%E3%82%BA-Sebastian-Raschka/dp/4839987807

## 📚 概要

このリポジトリには、大規模言語モデル（LLM）をゼロから構築するための Jupyter ノートブックが含まれています。書籍「つくりながら学ぶ！LLM 自作入門」に沿って、Transformer アーキテクチャと言語モデルの基礎を学習できます。

## 🔧 前提条件

- Python 3.8 以上
- Jupyter Notebook または JupyterLab
- Python と機械学習の基礎知識

## 📦 インストール方法

1. このリポジトリをクローン:
```bash
git clone https://github.com/kshr123/llm_from_scrach.git
cd llm_from_scrach
```

2. 仮想環境の作成（推奨）:
```bash
python -m venv venv
source venv/bin/activate  # Windows の場合: venv\Scripts\activate
```

3. 必要な依存関係をインストール:
```bash
pip install jupyter numpy torch transformers
```

## 🚀 使い方

Jupyter Notebook を起動:
```bash
jupyter notebook
```

任意のチャプターのノートブックを開いて、学習を開始してください！

## 📖 チャプター概要

| ノートブック | 内容 |
|----------|-------------|
| [ch03_multihead-attention.ipynb](ch03_multihead-attention.ipynb) | マルチヘッドアテンション機構の理解 |
| [ch04_GPTmodel.ipynb](ch04_GPTmodel.ipynb) | GPT モデルアーキテクチャの構築 |
| [ch05_pretraining.ipynb](ch05_pretraining.ipynb) | 言語モデルの事前学習 |
| [ch06_finetuning.ipynb](ch06_finetuning.ipynb) | 事前学習済みモデルのファインチューニング |

## 📂 プロジェクト構成

```
llm_from_scrach/
├── ch03_multihead-attention.ipynb
├── ch04_GPTmodel.ipynb
├── ch05_pretraining.ipynb
├── ch06_finetuning.ipynb
├── chapters_code/          # 各チャプターのサポートコード
├── fig/                    # 図とダイアグラム
└── README.md
```

## 📝 ライセンス

ライセンス情報については書籍を参照してください。

## 🙏 謝辞

Sebastian Raschka 著「つくりながら学ぶ！LLM 自作入門」に基づいています。
