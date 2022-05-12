WebSDR Cat-Control // Orbitron2WebSDR
此应用程序旨在通过WebSDR跟踪卫星无线电信号，同时通过使用卫星跟踪器“Orbitron”的MyDDE驱动器来考虑多普勒频移。

WebSDR（Web = 可通过互联网访问，SDR = 软件定义无线电）是在 Web 浏览器中运行的无线电接收器。它将业余无线电频段上收到的内容实时提供给互联网，并通过网页提供给所有感兴趣的听众。

“Orbitron”是一种卫星跟踪系统，供业余无线电爱好者和卫星观察员使用。它实时确定卫星的位置，无论您是想要在一天的当前时间还是稍后的信息。为了将卫星的多普勒频移接收频率转发给业余无线电接收器，需要为该接收器提供所谓的CAT控制驱动器。WebSDR无线电可以通过CAT-Control通过浏览器远程操作。

Orbitron为此提供了一个名为MyDDE的驱动程序。此驱动程序通过 DDE 传输接收频率。在计算中，DDE或Dynamic Data Exchange是Microsoft Windows和OS/2早期版本中使用的一种进程间通信技术。DDE 允许程序操作其他程序提供的对象，并响应影响这些对象的用户操作。

应用程序“WebSDR Cat-Control”现在通过MyDDE-Driver建立从Orbitron到WebSDR接收器的连接，并将卫星的多普勒频移接收频率转发给实时跟踪。WebSDR Cat-Control // Orbitron2WebSDR 是在 LabVIEW 2020 中开发的

要求：
1）Orbitron 3.71版本（在此下载：http://www.stoff.pl/)

2）MyDDE驱动程序（在这里下载：http://www.stoff.pl/orbitron/files/mydde.zip)

3）首选网络浏览器（推荐火狐浏览器;在这里下载：https://www.mozilla.org/en-US/firefox/new/)

4） LabVIEW 21 32 位 运行 引擎 （https://www.ni.com/de-de/support/downloads/software-products/download.labview-runtime.html#443250)

视频：
----------------

[![Orbitron2Websdr](https://user-images.githubusercontent.com/3606905/159119945-d6d3702a-a1e7-4796-a31f-a2ced8f14182.JPG)](https://www.youtube.com/watch?v=LkdO7o0-AwY)


[![image](https://user-images.githubusercontent.com/3606905/155881896-1a0cb6a4-7386-4a0d-8725-96ccdb60dfef.png)](https://www.youtube.com/watch?v=3J_UkhTQFNA)
