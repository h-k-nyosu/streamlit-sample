# Streamlit を使った大規模言語モデル活用のプロトタイピングをするためのスタートキットリポジトリ

デフォルトでは ChatGPT と会話ができるようになっている。

## 起動方法

```sh
# 環境構築
poetry install

# 起動
poetry run streamlit run app.py
```

## 環境変数

.env ファイルに OpenAI の API キーを記載する。

```python

OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

```
