# H29 情報組織化・検索論 演習ページ
山本 岳洋 (tyamamot at dl.kuis.kyoto-u.ac.jp)

## 概要
本リポジトリは，平成29年度『情報組織化・検索論』に対応するページです．講義で学んだアルゴリズムを実際のデータに適用するために必要な技術を学んでもらうことを目的としています．この演習のスタンスとして，アルゴリズムをゼロから実装するというよりは，可能な限り既存のライブラリやツールを使って，アルゴリズムを実際のデータに適用する事ができるようになることを重要視します．

## 環境設定

### pyenvとanacondaのインストール
本演習は，Pythonの各種環境・ライブラリを一括で用意できるanacondaを利用します．まずは，以下を参考に手元のマシンにanacondaをインストールしてください．

- 参考: https://qiita.com/shizuma/items/027167c6257f1c9d2a6f

### 1. homebrewとgitのインストール
- https://qiita.com/_daisuke/items/d3b2477d15ed2611a058 を参考にしてbrewをインストール
- https://qiita.com/micheleno13/items/133aee005ae37c28960e を参考にしてgitをインストール

### 2. pyenvのインストール
- https://qiita.com/shizuma/items/027167c6257f1c9d2a6f を参考にしてpyenvをインストールし，パスを通す

### 3. anacondaのインストール
```
git clone git://github.com/yyuu/pyenv-update.git ~/.pyenv/plugins/pyenv-update
pyenv update
pyenv install anaconda3-2.5.0
pyenv global anaconda3-2.5.0
conda install gensim
conda install networkx
```
- 詳しい人は，各自で好みの環境を構築してもらって構いません．

### 4. nltk corpusのインストール

pythonを起動し，以下のコマンドから，nltkのcorpusからstopwordsをインストールしておいてください．

```
$ python 
>>> import nltk
>>> nltk.download()
```

### 5. この演習コンテンツのダウンロードとnotebookの実行
適当なフォルダに移動してもらって，このリポジトリをクローンしてください．

```
$ git clone https://github.com/tyamamot/h29iro.git
```

anacondaが正常にインストールできていれば，ターミナル上で下記のコマンドを打てばブラウザ（http://localhost:8888）が立ち上がるはずです．

```
$ cd h29iro
$ ipython notebook
```

### 6. この演習コンテンツの更新
ローカルにあるこのリポジトリのフォルダに移動して，プルしてください．

```
$ cd h29iro
$ git pull
```



