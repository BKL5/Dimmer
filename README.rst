Arduino的调光器库
==============

这是一个Arduino软件库，用于使用双向可控硅和过零检测器电路控制交流负载。该库方法可用于通过单个共享的过零电路独立地控制多个三端双向可控硅开关的交流负载功率。

* Source code: https://github.com/circuitar/Dimmer
* Documentation: http://dimmer.readthedocs.org/
* 参考板: https://mdwdz.en.alibaba.com/product/60670737878-804998378/2CH_AC_LED_Light_Dimmer_Module_Controller_Board.html

有多种实现零交叉检测器电路的方法。该库基于上面的实现，但是可以很容易地修改为使用任何类型的过零检测器电路。

要安装，只需单击下载ZIP并使用Arduino IDE中的Sketch> Include Library ...> Add .ZIP Library进行安装。.

示例:

* Fade_ Arduino Fade example using an AC lamp.
* FadeMinimum_ Arduino Fade example using an AC lamp and setting a minimum power level (useful for dimmable LED or CFL lamps).
* RandomLamps_ Control 3 dimmable lamps with random values (can be extended to 10 lamps).
* WaveLamps_ Control 3 dimmable lamps in a wave form (can be extended to 10 lamps).
* CountMode_ Control high, low response AC loads without introducing noise using count mode.

.. _examples: https://github.com/circuitar/Dimmer/tree/master/examples/
.. _Fade: https://github.com/circuitar/Dimmer/blob/master/examples/Fade/Fade.ino
.. _FadeMinimum: https://github.com/circuitar/Dimmer/blob/master/examples/FadeMinimum/FadeMinimum.ino
.. _RandomLamps: https://github.com/circuitar/Dimmer/blob/master/examples/RandomLamps/RandomLamps.ino
.. _WaveLamps: https://github.com/circuitar/Dimmer/blob/master/examples/WaveLamps/WaveLamps.ino
.. _CountMode: https://github.com/circuitar/Dimmer/blob/master/examples/CountMode/CountMode.ino

----

Copyright (c) 2015 Circuitar  
All rights reserved.

This software is released under an MIT license. See the attached LICENSE file for details.
