jupyter-notebookを使ったPythonデータ分析
============================================

最近はやりのPythonデータ分析をjupyter-notebookを使って行う。

## 環境構築

vagrantで環境を作成。
vagrant環境にログインする必要はなくブラウザからvagrant環境のjupyterにアクセスして使用する。

(かなり時間がかかります。20min~）
```
$ vagrant up
```

**構築された環境について**

- anaconda(科学技術ライブラリなどが同梱されたpython環境)のダウンロードインストール
- condaからのjupyterのインストール
- fontなどの日本語対応
- jupyter-notebook
- vagrantでポートフォワーディング(host:8080 -> guest:8888)


## 目次

- [01-jupyter.md](01-jupyter.md) jupyter-notebook
- [02-numpy.md](02-numpy.md) numpy復習
- [03-pandas.md](03-pandas.md) pandas

