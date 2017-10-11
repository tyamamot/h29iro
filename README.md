# H29 情報組織化検索論 演習ページ
山本 岳洋 (tyamamot at dl.kuis.kyoto-u.ac.jp)

## 環境設定 pyenvとanacondaのインストール
- 参考: https://qiita.com/shizuma/items/027167c6257f1c9d2a6f

### 1. homebrewとgitのインストール
- https://qiita.com/_daisuke/items/d3b2477d15ed2611a058 を参考にしてbrewをインストール
- https://qiita.com/micheleno13/items/133aee005ae37c28960e を参考にしてgitをインストール

### 2. pyenvのインストール
- https://qiita.com/shizuma/items/027167c6257f1c9d2a6f を参考にしてpyenvとvirtualenvをインストールし，パスを通す

### 3. anacondaのインストール
- 分かる人は，適当に環境を構築してください

```
git clone git://github.com/yyuu/pyenv-update.git ~/.pyenv/plugins/pyenv-update
pyenv update
pyenv install anaconda3-2.5.0
pyenv global anaconda3-2.5.0
```