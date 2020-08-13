About patin hardware
========================
.. toctree::
   :maxdepth: 2
   :caption: Contents:

=======================
1. patin本体側
=======================
・username
 flrobotics

・hostname
 flrobotics

======================
2. pit側
======================
・username
 pi

・hostname
 raspberrypi

.. note::
 sshパスワードは聞いてください

=====================
3. 充電方法
=====================
#. patinをpitに載せる
#. pitにsshでログインする
#. ホームにあるch_on.shを実行する
 ``$./ch_on.sh``
4. ホームにあるwatch.cgiで監視する
   
   ``$ ./watch.cgi``
   
   連続的にチェックするなら
   
   ``$ watch ./watch.cgi``

