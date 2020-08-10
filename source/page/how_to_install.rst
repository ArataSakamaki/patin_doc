How to install ros package
=============================
.. toctree::
   :maxdepth: 2
   :caption: Contents:

1. ROSパッケージのリポジトリをクローンする
________________________________________________
 ``$git clone https://gitlab.com/trcp/trcp_patin.git``

2. リポジトリに移動する
--------
 ``$cd trcp_patin``

3. git submoduleで非公開パッケージの中身を追加する
____________________________________________________
 ``$git submodule update --init --recursive``
.. note::
 パスワードは聞いてください
