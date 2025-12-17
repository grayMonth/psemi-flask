# P講習演習課題
## 概要
これはP講習に関するFlask課題の内容になります．

## 実装内容
- タスクの作成/編集/削除

## 実行手順
以下はPythonの環境が構築されていることを前提とする．
1. 本プロジェクトをクローンする
2. 本プロジェクトをVScodeなどのエディターで開く．</br>VScodeなら"Ctrl + @"でコンソールを開く．
3. Pythonの仮想環境を構築するために以下のコマンドを実行する．
```
# 仮想環境の構築
python -m venv venv

(uvにてPythonの構築を行っている場合)
uv venv <仮想環境名(デフォルトは.venv)> (--python 3.xx)
例）uv venv

# 仮想環境のアクティベート
<仮想環境名>\Script\activate
```
4. 必要なPythonライブラリのインストールを行うため，以下のコマンドを実行する．
```
# ライブラリのインストール
pip install -r requirements.txt

# uvコマンドの場合
uv pip install -r requirements.txt
```
5. これによりapp.pyを実行して，開いたサーバにアクセスし，タスクの作成，編集，削除を行うことができる．
