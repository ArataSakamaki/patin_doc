How to bring up patin
========================
.. toctree::
   :maxdepth: 2
   :caption: Contents:
             
============================
1. minimal launch
============================
 ``$roslaunch patin_bringup patin_minimal_bringup.launch``
 
 以下のノードを起動している
 
  urg_node
   レーザレンジファインダ用のノード
  teleop
   ps3コントローラでpatinを動かすノード
  controller
   rosと内部マイコンの通信用ノード
  state_publisher
   robotのモデルとtfを発行するノード

===========================
2. full launch
===========================
 ``$roslaunch patin_bringup patin_minimal_bringup.launch``

 以下のノードを起動している

  上記のノード+
  
  navigation
  
  amcl
  
