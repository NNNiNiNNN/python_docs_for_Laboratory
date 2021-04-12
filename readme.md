研究室でのコーディング教育用資料です。

# やってほしいこと

* 環境構築
  * わかる人は飛ばしてヨシ
* Basisフォルダ内のtest.pythonを動かす
* Basisフォルダ内のBasis.ipynbをjupyter notebookから動かすこと。
* ForLaboratoryフォルダ内のLIFmodel.ipynbを動かすこと。
* LIFモデルを自力で実装すること。

## 環境構築

エディタの導入、Python環境構築を行う。

わかる人は飛ばして問題ないです。

### 1. エディタを導入する

VScodeを導入します。エディタに指定はないので、わかる人は他の物で結構です。

[windows用導入手順](https://sukkiri.jp/technologies/devtools/vscode_win.html)

[mac用導入手順](https://sukkiri.jp/technologies/devtools/vscode_mac.html)



### 2. Pythonを導入する

anacondaを用いて環境導入を行います。わかる人は他の開発環境を使っても結構です。

以下のリンクを元に、環境構築を行ってください。

[5分で簡単！AnacondaでPython3をインストール(Windows/Mac編)](https://ai-inter1.com/python-install/)

### 3. 動作テスト

対話モードでpythonを動かしてみる。

コマンドプロンプト(win)、ターミナル(mac)を開く。

```
python
```
と入力してエンター。

```
>>>
```

上記のような表示が出ればとりあえず成功、対話モードが起動しました。

ハローワールドしてみよう。以下のように書いてエンター。

```
>>> print("Hello, World!")
```
Hello, World!と表示が出れば成功。

ctrl(command)+Zを同時押しで対話モードを終了します。

## 動かしてみよう

ここに書いてあるコードをダウンロードしてみよう。

右上のCode▽をクリック、Download ZIPを押してダウンロード、解凍してください。

### 1. HelloWorld.py

まずはHelloWorld.pyを実行してみてください。

ターミナル/コマンドプロンプトにてBasisフォルダを開きます。

```
cd フォルダ名
```

Basisフォルダ内にはHelloWorld.py、Basis.ipynbの二つのファイルが置いてあります。

HelloWorld.pyを実行してみます。

```
python HelloWorld.py
```

これでHelloWorldと出れば成功です。

### Basis.ipynb

次にBasis.ipynbを実行してみます。これはjupyter notebookというツールを使って開きます。(anacondaと同時に導入されているはずです)

[このリンクなど](https://udemy.benesse.co.jp/development/python-work/jupyter-notebook.html)を参考に起動し、Basis.ipynbを開いてみてください。

書いてあるコードを一通り実行できたらOK。

### LIFmodel.ipynb

python_docs_for_Laboratory/ForLaboratoryフォルダに移動します。

同様にLIFmodel.ipynbを実行。

書いてあるコードを一通り実行できればOK、ここに書いてあるアルゴリズムを自力で実装できればとりあえず目標達成です。

## メモ 

### フォルダ構成



#### Basis
jupyter notebookで動くようにしています。

pythonの基礎の基礎だけ載せています。
* Hello World!
* for文の使い方
* numpy
* グラフの表示
* ファイルへの出力

必要であろう基礎情報をまとめただけなので特に読まなくていい。

#### ForLaboratory

LIF(leaky-integrate-and-fire)モデルのグラフ表示を目標に書いています。

jupyter notebookで動くようにしています。必ず自分で動かしてみること、できればLIFモデルの自力での実装までしてほしい。

#### others

* 現状何もないです。