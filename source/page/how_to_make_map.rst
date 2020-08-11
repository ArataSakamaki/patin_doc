How to make map
=================
.. toctree::
   :maxdepth: 2
   :caption: Contents:

====================================
1. hector slam
====================================
1. hector slam を起動する
 ``$roslaunch patin_map hector.launch``

2. mapが綺麗にある程度できたら保存する
 ``$rosrun map_server map_saver``


====================================
2. cartographer
====================================
1. cartographerを起動する
 ``$roslaunch patin_map cartographer.launch``

2. mapが綺麗にある程度できたら保存する
 ``rosrun patin_map cartographer_map_saver``


===================================
3. gmapping
===================================
まだできてない
