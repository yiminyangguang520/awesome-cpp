# Awesome C/C++
关于 C++ 框架、库和资源的一些汇总列表，由 [fffaraz ](https://github.com/fffaraz/awesome-cpp/) 发起和维护。

内容包括：标准库、Web应用框架、人工智能、数据库、图片处理、机器学习、日志、代码分析等。

- [Awesome C/C++](#awesome-cpp)
	- [Standard Libraries](#standard-libraries)
	- [Frameworks](#frameworks)
	- [Artificial Intelligence](#artificial-intelligence)
	- [Asynchronous Event Loop](#asynchronous-event-loop)
	- [Audio](#audio)
	- [Biology](#biology)
	- [Compression](#compression)
	- [Concurrency](#concurrency)
	- [Containers](#containers)
	- [Cryptography](#cryptography)
	- [Database](#database)
	- [Debug](#debug)
	- [Game Engine](#game-engine)
	- [GUI](#gui)
	- [Graphics](#graphics)
	- [Image Processing](#image-processing)
	- [Internationalization](#internationalization)
	- [JSON](#json)
	- [Logging](#logging)
	- [Machine Learning](#machine-learning)
	- [Math](#math)
	- [Multimedia](#multimedia)
	- [Networking](#networking)
	- [Physics](#physics)
	- [Robotics](#robotics)
	- [Scientific Computing](#scientific-computing)
	- [Scripting](#scripting)
	- [Serialization](#serialization)
	- [Video](#video)
	- [Virtual Machines](#virtual-machines)
	- [Web Application Framework](#web-application-framework)
	- [XML](#xml)
	- [Miscellaneous](#miscellaneous)
- [Software](#software)
	- [Compiler](#compiler)
	- [Online Compiler](#online-compiler)
	- [Debugger](#debugger)
	- [Integrated Development Environment](#integrated-development-environment)
	- [Build Systems](#build-systems)
	- [Static Code Analysis](#static-code-analysis)
- [Resources](#resources)
	- [API Design](#api-design)
	- [Articles](#articles)
	- [Books](#books)
	- [Coding Style](#coding-style)
	- [Videos](#videos)
	- [Websites](#websites)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## 标准库
*包括了STL容器，算法和函数等。*

* [C++ Standard Library](http://en.wikipedia.org/wiki/C%2B%2B_Standard_Library) - 是一系列类和函数的集合，使用核心语言编写，也是C++ISO自身标准的一部分.
* [Standard Template Library](http://en.wikipedia.org/wiki/Standard_Template_Library) - 准模板库 (STL).
* [C POSIX library](http://en.wikipedia.org/wiki/C_POSIX_library) - POSIX系统的C标准库规范.
* [ISO C++ Standards Committee](https://github.com/cplusplus) - ISO/IEC JTC1/SC22/WG21 - C++标准委员会. [website](http://www.open-std.org/JTC1/SC22/WG21/)

## 框架
*C++通用框架和库.*

* [Apache C++ Standard Library](http://stdcxx.apache.org/) - 是一系列算法，容器，迭代器和其他基本组件的集合. [Apache2]
* [ASL](http://stlab.adobe.com/) - Adobe源代码库提供了同行的评审和可移植的C++源代码库. [MIT]
* [Boost](https://github.com/boostorg) :star: - 大量通用C++库的集合. [Boost] [website](http://www.boost.org/)
* [BDE](https://github.com/bloomberg/bde) - 来自于BDE讯实验室的开发环境. [MIT]
* [Cinder](http://libcinder.org/) - 提供专业品质创造性编码的开源开发社区. [BSD]
* [Cxxomfort](http://ryan.gulix.cl/fossil.cgi/cxxomfort/) - 轻量级的，只包含头文件的库，将C++ 11的一些新特性移植到C++03中. [MIT]
* [Dlib](http://dlib.net/) :star: - 使用契约式编程和现代C++科技设计的通用的跨平台的C++库. [Boost]
* [EASTL](https://github.com/paulhodge/EASTL) - EA-STL公共部分. [BSD]
* [ffead-cpp](https://github.com/sumeetchhetri/ffead-cpp) - 企业应用程序开发框架. [Apache2]
* [Folly](https://github.com/facebook/folly) - 由Facebook开发和使用的开源C++库. [Apache2]
* [JUCE](https://github.com/julianstorer/JUCE) - 包罗万象的C++类库，用于开发跨平台软件. [Core-Module: ISC, Rest: GPL2/GPL3/Commercial] [website](http://www.juce.com/)
* [libPhenom](https://github.com/facebook/libphenom) - 用于构建高性能和高度可扩展性系统的事件框架. [Apache2]
* [LibSourcey](https://github.com/sourcey/libsourcey) - 用于实时的视频流和高性能网络应用程序的C++11事件IO. [LGPL]
* [LibU](https://github.com/koanlogic/libu) - C语言写的多平台工具库. [BSD]
* [Loki](http://loki-lib.sourceforge.net/) - C++库的设计，包括常见的设计模式和习语的实现. [MIT]
* [MiLi](https://code.google.com/p/mili/) - 只含头文件的小型C++库. [Boost]
* [openFrameworks](http://www.openframeworks.cc/) - 开发C++工具包，用于创意性编码. [MIT]
* [Qt](http://qt-project.org/) :star: - 跨平台的应用程序和用户界面框架. [LGPL]
* [Reason](http://code.google.com/p/reason/) - 跨平台的框架，使开发者能够更容易地使用Java，.Net和Python，同时也满足了他们对C++性能和优势的需求. [GPLv2]
* [ROOT](http://root.cern.ch) - 具备所有功能的一系列面向对象的框架，能够非常高效地处理和分析大量的数据，为欧洲原子能研究机构所用. [LGPL]
* [STLport](http://www.stlport.org/) - 是STL具有代表性的版本. [Free]
* [STXXL](http://stxxl.sourceforge.net/) - 用于额外的大型数据集的标准模板库. [Boost]
* [Ultimate++](http://www.ultimatepp.org/) - C++跨平台快速应用程序开发框架. [BSD]
* [Windows Template Library](http://sourceforge.net/projects/wtl/) - 用于开发Windows应用程序和UI组件的C++库. [Public]
* [Yomm11](https://github.com/jll63/yomm11) - C++11的开放multi-methods. [Boost]

## 人工智能

* [btsk](https://github.com/aigamedev/btsk) - 游戏行为树启动器工具. [zlib]
* [Evolving Objects](http://eodev.sourceforge.net/) - 基于模板的，ANSI C++演化计算库，能够帮助你非常快速地编写出自己的随机优化算法. [LGPL]
* [Neu](https://github.com/andrometa/neu) - C++11框架，编程语言集，用于创建人工智能应用程序的多用途软件系统. [BSD]

## 异步事件循环

* [Boost.Asio](http://think-async.com/) - 用于网络和底层I/O编程的跨平台的C++库. [Boost]
* [libev](http://libev.schmorp.de/) - 功能齐全，高性能的时间循环，轻微地仿效libevent，但是不再像libevent一样有局限性，也修复了它的一些bugs. [BSD and GPL]
* [libevent](http://libevent.org/) - 事件通知库. [BSD]
* [libuv](https://github.com/joyent/libuv) - 跨平台异步I/O. [BSD]

## 音频
*音频，声音，音乐，数字化音乐库*

* [FMOD](http://www.fmod.org/) - 易于使用的跨平台的音频引擎和音频内容的游戏创作工具. [Free for non-commercial/Commercial]
* [Maximilian](https://github.com/micknoise/Maximilian) - C++音频和音乐数字信号处理库. [MIT]
* [OpenAL](http://www.openal.org/) - 开源音频库—跨平台的音频API. [BSD/LGPL/Commercial]
* [Opus](http://opus-codec.org/) - 一个完全开放的，免版税的，高度通用的音频编解码器. [BSD]
* [Speex](http://www.speex.org/) - 免费编解码器，为Opus所废弃. [BSD]
* [Tonic](https://github.com/TonicAudio/Tonic) - C++易用和高效的音频合成. [Unlicense]
* [Vorbis](http://xiph.org/vorbis/) - Ogg Vorbis是一种完全开放的，非专有的，免版税的通用压缩音频格式. [BSD]

## 生态学
*生物信息，基因组学和生物技术*

* [libsequence](http://molpopgen.github.io/libsequence/) - 用于表示和分析群体遗传学数据的C++库. [GPL]
* [SeqAn](http://www.seqan.de/) - 专注于生物数据序列分析的算法和数据结构. [BSD/3-clause]
* [Vcflib](https://github.com/ekg/vcflib) - 用于解析和处理VCF文件的C++库. [MIT]
* [Wham](https://github.com/jewmanchue/wham) - 直接把联想测试应用到BAM文件的基因结构变异. 
	
## 压缩
*压缩和归档库*

* [bzip2](http://www.bzip.org/) - 一个完全免费，免费专利和高质量的数据压缩. [BSD]
* [doboz](https://bitbucket.org/attila_afra/doboz/overview) - 能够快速解压缩的压缩库. [zlib]
* [PhysicsFS](https://icculus.org/physfs/) - 对各种归档提供抽象访问的库，主要用于视频游戏，设计灵感部分来自于Quake3的文件子系统. [zlib]
* [KArchive](https://projects.kde.org/projects/frameworks/karchive) - 用于创建，读写和操作文件档案（例如zip和 tar）的库，它通过QIODevice的一系列子类，使用gzip格式，提供了透明的压缩和解压缩的数据. [LGPL]
* [LZ4](https://code.google.com/p/lz4/) - 非常快速的压缩算法. [BSD]
* [LZHAM](https://code.google.com/p/lzham/) - 无损压缩数据库，压缩比率跟LZMA接近，但是解压缩速度却要快得多. [BSD]
* [LZMA](http://www.7-zip.org/sdk.html) :star: - 7z格式默认和通用的压缩方法. [LGPL]
* [LZMAT](http://www.matcode.com/lzmat.htm) - 及其快速的实时无损数据压缩库. [GPL]
* [miniz](https://code.google.com/p/miniz/) - 单一的C源文件，紧缩/膨胀压缩库，使用zlib兼容API，ZIP归档读写，PNG写方式. [Unlicense]
* [Minizip](https://github.com/nmoinvaz/minizip) - Zlib最新bug修复，支持PKWARE磁盘跨越，AES加密和IO缓冲. [zlib]
* [Snappy](https://code.google.com/p/snappy/) - 快速压缩和解压缩. [BSD]
* [ZLib](http://zlib.net/) - 非常紧凑的数据流压缩库. [zlib]
* [ZZIPlib](http://zziplib.sourceforge.net/) - 提供ZIP归档的读权限. [MPL/LGPL]

## 并发性
*并发执行和多线程*

* [Boost.Compute](https://github.com/kylelutz/compute) - 用于OpenCL的C++GPU计算库. [Boost]
* [Bolt](https://github.com/HSA-Libraries/Bolt) - 针对GPU进行优化的C++模板库. [Apache2]
* [C++React](https://github.com/schlangster/cpp.react) - 用于C++11的反应性编程库. [Boost]
* [Intel TBB](https://www.threadingbuildingblocks.org/) - Intel线程构件块. [GPLv2 with runtime exception]
* [Libclsph](https://github.com/libclsph/libclsph) - 基于OpenCL的GPU加速SPH流体仿真库. [MIT]
* [OpenCL](https://www.khronos.org/opencl/) - 并行编程的异构系统的开放标准.
* [OpenMP](http://openmp.org/) - The OpenMP API.
* [Thrust](http://thrust.github.io/) - 类似于C++标准模板库的并行算法库. [Apache2]
* [HPX](https://github.com/STEllAR-GROUP/hpx/) - 用于任何规模的并行和分布式应用程序的通用C++运行时系统. [Boost]
* [VexCL](https://github.com/ddemidov/vexcl) - 用于OpenCL/CUDA 的C++向量表达式模板库. [MIT]

## 容器

* [C++ B-tree](https://code.google.com/p/cpp-btree/) - 基于B树数据结构，实现命令内存容器的模板库. [Apache2]
* [Hashmaps](https://github.com/goossaert/hashmap) - C++中开放寻址哈希表算法的实现. [MIT]

## 密码学
*加密与解密库*

* [Bcrypt](http://bcrypt.sourceforge.net/) - 一个跨平台的文件加密工具，加密文件可以移植到所有可支持的操作系统和处理器中. 
* [BeeCrypt]()
* [Botan](http://botan.randombit.net/) - C++加密库. [BSD-2]
* [Crypto++](http://www.cryptopp.com/) - 一个有关加密方案的免费的C++库. [Boost]
* [GnuPG](https://www.gnupg.org/) - OpenPGP标准的完整实现. [GPL]
* [GnuTLS](http://www.gnutls.org/) - 实现了SSL，TLS和DTLS协议的安全通信库. [LGPLv2.1]
* [Libgcrypt](http://www.gnu.org/software/libgcrypt/)
* [libmcrypt]()
* [LibreSSL](http://www.libressl.org/) - 免费的SSL/TLS协议，属于2014 OpenSSL的一个分支. [?]
* [libsodium](https://github.com/jedisct1/libsodium) - 基于NaCI的加密库，固执己见，容易使用. [ISC]
* [LibTomCrypt](https://github.com/libtom/libtomcrypt) - 一个非常全面的，模块化的，可移植的加密工具. [WTFPL]
* [Nettle](http://www.lysator.liu.se/~nisse/nettle/) - 底层的加密库. [LGPL]
* [OpenSSL](http://www.openssl.org/) - 一个强大的，商用的，功能齐全的，开放源代码的加密库. [Apache]
* [Tiny AES128 in C](https://github.com/kokke/tiny-AES128-C) - 用C实现的一个小巧，可移植的实现了AES128ESB的加密算法. [PublicDomain]

## 数据库
*数据库，SQL服务器，ODBC驱动程序和工具*

* [hiberlite](https://github.com/paulftw/hiberlite) - 用于Sqlite3的C++对象关系映射. [BSD]
* [Hiredis](https://github.com/redis/hiredis) - 用于Redis数据库的很简单的C客户端库. [BSD]
* [LevelDB](https://github.com/google/leveldb) - 快速键值存储库. [BSD]
* [LMDB](http://symas.com/mdb/) - 符合数据库四大基本元素的嵌入键值存储. [OpenLDAP]
* [MySQL++](http://www.tangentsoft.net/mysql++/) - 封装了MySql的C API的C++ 包装器. [LGPL]
* [RocksDB](https://github.com/facebook/rocksdb) - 来自Facebook的嵌入键值的快速存储. [BSD]
* [SQLite](http://www.sqlite.org/) - 一个完全嵌入式的，功能齐全的关系数据库，只有几百KB，可以正确包含到你的项目中. [PublicDomain]

## 调试
*调试库， 内存和资源泄露检测，单元测试*

* [Boost.Test](http://www.boost.org/doc/libs/master/libs/test/doc/html/index.html) - Boost测试库. [Boost]
* [Catch](https://github.com/philsquared/Catch) - 一个很时尚的，C++原生的框架，只包含头文件，用于单元测试，测试驱动开发和行为驱动开发. [Boost]
* [CppUnit](http://www.freedesktop.org/wiki/Software/cppunit/) - 由JUnit移植过来的C++测试框架. [LGPLv2]
* [CTest](http://www.cmake.org/cmake/help/v2.8.8/ctest.html) - CMake测试驱动程序. [BSD]
* [googletest](http://code.google.com/p/googletest/) - 谷歌C++测试框架. [BSD]
* [ig-debugheap](https://github.com/deplinenoise/ig-debugheap) - 用于跟踪内存错误的多平台调试堆. [BSD]
* [libtap](https://github.com/zorgnax/libtap) - 用C语言编写测试. [GPLv2]
* [MemTrack](http://www.almostinfinite.com/memtrack.html) - 用于C++跟踪内存分配.
* [microprofile](https://bitbucket.org/jonasmeyer/microprofile/overview) - 跨平台的网络试图分析器. [PublicDomain]
* [minUnit](http://www.jera.com/techinfo/jtns/jtn002.html) - 使用C写的迷你单元测试框架，只使用了两个宏. [PublicDomain]
* [Remotery](https://github.com/Celtoys/Remotery) - 用于web视图的单一C文件分析器. [Apache2]
* [UnitTest++](http://unittest-cpp.sourceforge.net/) - 轻量级的C++单元测试框架. [MIT/X Consortium license]

## 游戏引擎

* [Cocos2d-x](http://www.cocos2d-x.org/) - 一个跨平台框架，用于构建2D游戏，互动图书，演示和其他图形应用程序. [Commercial?]
* [Grit](http://gritengine.com/) - 社区项目，用于构建一个免费的游戏引擎，实现开放的世界3D游戏. [MIT]
* [Irrlicht](http://irrlicht.sourceforge.net/) - C++语言编写的开源高性能的实时3D引擎. [zlib]
* [Polycode](http://polycode.org/) - C++实现的用于创建游戏的开源框架(与Lua绑定). [MIT]

## GUI
*图形用户界面*

* [CEGUI](http://cegui.org.uk/) - 很灵活的跨平台GUI库. 
* [FLTK](http://www.fltk.org/index.php) - 快速，轻量级的跨平台的C++GUI工具包. [GPLv2]
* [GTK+](http://www.gtk.org/) - 用于创建图形用户界面的跨平台工具包. [LGPL]
* [gtkmm](http://www.gtkmm.org/en/) - 用于受欢迎的GUI库GTK+的官方C++接口. [LGPL]
* [imgui](https://github.com/ocornut/imgui) - 拥有最小依赖关系的立即模式图形用户界面. [MIT]
* [libRocket](http://librocket.com/) - C++ HTML/CSS 游戏接口中间件. [MIT]
* [MyGUI](http://mygui.info/) - 快速，灵活，简单的GUI. [MIT]
* [Ncurses](http://invisible-island.net/ncurses/) - 终端用户界面. [MIT]
* [QCustomPlot](http://qcustomplot.com/) - 没有更多依赖关系的Qt绘图控件. [GPLv3]
* [Qwt](http://qwt.sourceforge.net/) - 用户与技术应用的Qt 控件. [Own based on LGPL]
* [QwtPlot3D](http://qwtplot3d.sourceforge.net/) - 功能丰富的基于Qt/OpenGL的C++编程库，本质上提供了一群3D控件. [zlib]
* [OtterUI](https://github.com/Twolewis/OtterUI) - 嵌入式系统和互动娱乐软件的用户界面开发解决方案. [MIT]
* [PDCurses](http://pdcurses.sourceforge.net/) - 包含源代码和预编译库的公共图形函数库. [PublicDomain]
* [wxWidgets](http://wxwidgets.org/) - C++库，允许开发人员使用一个代码库可以为widows， Mac OS X，Linux和其他平台创建应用程序. [Own LGPL]

## 图形

* [bgfx](https://github.com/bkaradzic/bgfx) - 跨平台的渲染库. [BSD]
* [Cairo](http://www.cairographics.org/) - 支持多种输出设备的2D图形库. [LGPLv2 or Mozilla MPL]
* [Horde3D](https://github.com/horde3d/Horde3D) - 一个小型的3D渲染和动画引擎. [EPL]
* [magnum](https://github.com/mosra/magnum) - C++11和OpenGL 2D/3D 图形引擎. [MIT] [website](http://mosra.cz/blog/magnum.php)
* [Ogre 3D](http://www.ogre3d.org/) :star: - 用C++编写的一个面向场景，实时，灵活的3D渲染引擎(并非游戏引擎). [MIT]
* [OpenSceneGraph](http://www.openscenegraph.org/) - 具有高性能的开源3D图形工具包. [OSGPL]
* [Panda3D](http://www.panda3d.org/) - 用于3D渲染和游戏开发的框架，用Python和C++编写. [BSD]
* [Skia](https://github.com/google/skia) - 用于绘制文字，图形和图像的完整的2D图形库. [bSD] [webpage](https://sites.google.com/site/skiadocs/home)
* [urho3d](https://github.com/urho3d/Urho3D) - 跨平台的渲染和游戏引擎. [Many different, mostly MIT]

## 图像处理

* [Boost.GIL](http://www.boost.org/doc/libs/1_56_0/libs/gil/doc/index.html) - 通用图像库.
* [CImg](http://cimg.sourceforge.net/) - 用于图像处理的小型开源C++工具包. [Own LGPL or GPL]
* [CxImage](http://www.xdp.it/cximage.htm) - 用于加载，保存，显示和转换的图像处理和转换库，可以处理的图片格式包括 BMP, JPEG, GIF, PNG, TIFF, MNG, ICO, PCX, TGA, WMF, WBMP, JBG, J2K. [zlib]
* [FreeImage](http://freeimage.sourceforge.net/) - 开源库，支持现在多媒体应用所需的通用图片格式和其他格式. [GPLv2 or GPLv3]
* [GDCM](http://gdcm.sourceforge.net/wiki/index.php/Main_Page) - Grassroots DICOM 库.
* [ITK](http://www.itk.org/) - 跨平台的开源图像分析系统. [Apache 2.0 from ITK 4.0]
* [Magick++](http://www.imagemagick.org/script/api.php) - ImageMagick程序的C++接口. [Apache 2.0]
* [MagickWnd](http://www.imagemagick.org/script/api.php) - ImageMagick程序的C接口. [Apache 2.0]
* [OpenCV](http://opencv.org/) :star: - 开源计算机视觉类库. [BSD]
* [tesseract-ocr](https://code.google.com/p/tesseract-ocr/) - OCR引擎. [Apache 2.0]
* [VIGRA](https://github.com/ukoethe/vigra) - 用于图像分析通用C++计算机视觉库. [MIT X11]
* [VTK](http://www.vtk.org/) - 用于3D计算机图形学，图像处理和可视化的开源免费软件系统. [BSD]

## 国际化

* [gettext](http://www.gnu.org/software/gettext/) - GNU `gettext'. [GPLv2]
* [IBM ICU](http://site.icu-project.org/) - 提供Unicode 和全球化支持的C、C++ 和Java库. [ICU]
* [libiconv](http://www.gnu.org/software/libiconv/) - 用于不同字符编码之间的编码转换库. [GPL]

## JSON

* [frozen](https://github.com/cesanta/frozen) - C/C++的JSON解析生成器. [GPL & GPLv2]
* [Jansson](https://github.com/akheron/jansson) - 进行编解码和处理JSON数据的C语言库. [MIT]
* [jbson](https://github.com/chrismanning/jbson) - C++14中构建和迭代BSON data,和JSON 文档的库. [Boost]
* [JeayeSON](https://github.com/jeaye/jeayeson) - 非常健全的C++ JSON库，只包含头文件. [BSD]
* [JSON++](https://github.com/hjiang/jsonxx) - C++ JSON 解析器. [MIT]
* [json-parser](https://github.com/udp/json-parser) - 用可移植的ANSI C编写的JSON解析器，占用内存非常少. [BSD]
* [json11](https://github.com/dropbox/json11) - 一个迷你的C++11 JSON库. [MIT]
* [jute](https://github.com/amir-s/jute) - 非常简单的C++ JSON解析器. [PublicDomain]
* [libjson](https://github.com/vincenthz/libjson) - C语言中的JSON解析和打印库，很容易和任何模型集成. [LGPL]
* [libjson](http://sourceforge.net/projects/libjson/) - 轻量级的JSON库. [?]
* [PicoJSON](https://github.com/kazuho/picojson) - C++中JSON解析序列化，只包含头文件. [BSD]
* [qt-json](https://github.com/gaudecker/qt-json) - 用于JSON数据和 QVariant层次间的相互解析的简单类. [GPLv3]
* [QJson](https://github.com/flavio/qjson) - 将JSON数据映射到QVariant对象的基于Qt的库. [LGPLv2]
* [RapidJSON](https://github.com/miloyip/rapidjson) :star: - 用于C++的快速JSON 解析生成器，包含SAX和DOM两种风格的API. [MIT]
* [YAJL](https://github.com/lloyd/yajl) - C语言中快速流JSON解析库. [ISC]

## 日志

* [Boost.Log](http://www.boost.org/doc/libs/1_56_0/libs/log/doc/html/index.html) - 设计非常模块化，并且具有扩展性. [Boost]
* [easyloggingpp](https://github.com/easylogging/easyloggingpp) - C++日志库，只包含单一的头文件. [MIT] [website](http://easylogging.org/)
* [Log4cpp](http://log4cpp.sourceforge.net/) - 一系列C++类库，灵活添加日志到文件，系统日志，IDSA和其他地方. [LGPL]
* [templog](http://www.templog.org/) - 轻量级C++库，可以添加日志到你的C++应用程序中. [Boost]

## 机器学习

* [Caffe](https://github.com/BVLC/caffe) - 快速的神经网络框架. [BSD]
* [CCV](https://github.com/liuliu/ccv) - 以C语言为核心的现代计算机视觉库. [BSD]
* [mlpack](http://www.mlpack.org/) - 可扩展的C++机器学习库. [LGPLv3]
* [OpenCV](https://github.com/Itseez/opencv) :star: - 开源计算机视觉库. [BSD] [website](http://opencv.org/)
* [Recommender](https://github.com/GHamrouni/Recommender) - 使用协同过滤进行产品推荐/建议的C语言库. [BSD]
* [SHOGUN](https://github.com/shogun-toolbox/shogun) - Shogun 机器学习工具. [GPLv3]
* [sofia-ml](https://code.google.com/p/sofia-ml/) - 用于机器学习的快速增量算法套件. [Apache2]

## 数学

* [Armadillo](http://arma.sourceforge.net/) - 高质量的C++线性代数库，速度和易用性做到了很好的平衡。语法和MatlAB很相似. [MPL2]
* [blaze](https://code.google.com/p/blaze-lib/) - 高性能的C++数学库，用于密集和稀疏算法. [BSD]
* [ceres-solver](http://ceres-solver.org/) - 来自谷歌的C++库，用于建模和解决大型复杂非线性最小平方问题. [BSD]
* [CGal](http://www.cgal.org/) - 高效，可靠的集合算法集合. [LGPL&GPL]
* [cml](http://cmldev.net/) - 用于游戏和图形的免费C++数学库. [Boost]
* [Eigen](http://eigen.tuxfamily.org/) - 高级C++模板头文件库，包括线性代数，矩阵，向量操作，数值解决和其他相关的算法. [MPL2]
* [GMTL](http://ggt.sourceforge.net/) - 数学图形模板库是一组广泛实现基本图形的工具. [GPLv2]
* [GMP](https://gmplib.org/) - 用于个高精度计算的C/C++库，处理有符号整数，有理数和浮点数. [LGPLv3 and GPLv2]

## 多媒体

* [GStreamer](http://gstreamer.freedesktop.org/) - 构建媒体处理组件图形的库. [LGPL]
* [LIVE555 Streaming Media](http://www.live555.com/liveMedia/) - 使用开放标准协议(RTP/RTCP, RTSP, SIP) 的多媒体流库 (RTP/RTCP, RTSP, SIP). [LGPL]
* [libVLC](https://wiki.videolan.org/LibVLC) - libVLC (VLC SDK)媒体框架. [GPL]
* [QtAv](https://github.com/wang-bin/QtAV) - 基于Qt和FFmpeg的多媒体播放框架，能够帮助你轻而易举地编写出一个播放器. [LGPL] [website](http://wang-bin.github.io/QtAV/)
* [SDL](http://www.libsdl.org/) :star: - 简单直控媒体层. [zlib]
* [SFML](http://www.sfml-dev.org/) :star: - 快速，简单的多媒体库. [zlib]

## 网络

* [ACE](http://www.cs.wustl.edu/~schmidt/ACE.html) - C++面向对象网络变成工具包. [?MIT?]
* [Boost.Asio](http://think-async.com/) :star: - 用于网络和底层I/O编程的跨平台的C++库. [Boost]
* [Casablanca](http://casablanca.codeplex.com/) - C++ REST SDK. [Apache2]
* [cpp-netlib](http://cpp-netlib.org/) - 高级网络编程的开源库集合. [Boost]
* [Dyad.c](https://github.com/rxi/dyad) - C语言的异步网络. [MIT]
* [libcurl](http://curl.haxx.se/libcurl/) - 多协议文件传输库. [MIT/X derivate license]
* [Mongoose](https://github.com/cesanta/mongoose) - 非常轻量级的网络服务器. [GPLv2]
* [Muduo](https://github.com/chenshuo/muduo) - 用于Linux多线程服务器的C++非阻塞网络库. [BSD]
* [net_skeleton](https://github.com/cesanta/net_skeleton) - C/C++的TCP 客户端/服务器库. [GPLv2]
* [nope.c](https://github.com/riolet/nope.c) - 基于C语言的超轻型软件平台，用于可扩展的服务器端和网络应用。 对于C编程人员，可以考虑node.js. [GPLv2]
* [Onion](https://github.com/davidmoreno/onion) - C语言HTTP服务器库，其设计为轻量级，易使用. [Apache2/GPLv2]
* [POCO](https://github.com/pocoproject) :star: - 用于构建网络和基于互联网应用程序的C++类库，可以运行在桌面，服务器，移动和嵌入式系统. [Boost] [website](http://pocoproject.org/)
* [RakNet](https://github.com/OculusVR/RakNet) - 为游戏开发人员提供的跨平台的开源C++网络引擎. [BSD]
* [Tufão](https://github.com/vinipsmaker/tufao) - 用于Qt之上的C++构建的异步Web框架. [LGPLv2]
* [WebSocket++](https://github.com/zaphoyd/websocketpp) - 基于C++/Boost Aiso的websocket 客户端/服务器库. [BSD]
* [ZeroMQ](http://zeromq.org/) - 高速，模块化的异步通信库. [LGPL]

## 物理学
*动力学仿真引擎*

* [Box2D](https://code.google.com/p/box2d/) - 2D的游戏物理引擎. [BSD-like]
* [Bullet](https://github.com/bulletphysics/bullet3) - 3D的游戏物理引擎. [zlib] [website](http://bulletphysics.org)
* [Chipmunk](https://github.com/slembcke/Chipmunk2D) - 快速，轻量级的2D游戏物理库. [MIT] [website](https://chipmunk-physics.net/)
* [LiquidFun](https://github.com/google/liquidfun) - 2D的游戏物理引擎. [BSD-like]
* [Newton Dynamics](https://github.com/MADEAPPS/newton-dynamics) - 集成的解决方案实时仿真的物理环境. [zlib]
* [ODE](http://www.ode.org/) - 开放动力学引擎-开源，高性能库，模拟刚体动力学. [BSD&LGPL]
* [ofxBox2d](https://github.com/vanderlin/ofxBox2d) - Box2D开源框架包装器D. [BSD-like]
* [Simbody](https://github.com/simbody/simbody) - 高性能C++多体动力学/物理库，模拟关节生物力学和机械系统，像车辆，机器人和人体骨骼. [Apache2]

## 机器人学

* [MOOS-IvP](http://moos-ivp.org) - 一组开源C++模块，提供机器人平台的自主权，尤其是自主的海洋车辆.
* [MRPT](http://www.mrpt.org/) - 移动机器人编程工具包. [BSD]
* [PCL](https://github.com/PointCloudLibrary/pcl) - 点云库是一个独立的，大规模的开放项目，用于2D/3D图像和点云处理 [BSD] [website](http://www.pointclouds.org/)
* [Robotics Library (RL)](http://www.roboticslibrary.org/) - 一个独立的C++库，包括机器人动力学，运动规划和控制. [BSD]
* [RobWork](http://www.robwork.dk/jrobwork/) - 一组C++库的集合，用于机器人系统的仿真和控制. [Apache2]
* [ROS](http://wiki.ros.org/) - 机器人操作系统，提供了一些库和工具帮助软件开发人员创建机器人应用程序. [BSD]

## 科学计算
* [FFTW](http://www.fftw.org/) - 用一维或者多维计算DFT的C语言库. [GPL]
* [GSL](http://www.gnu.org/software/gsl/) - GNU科学库. [GPL]

## 脚本

* [ChaiScript](https://github.com/ChaiScript/ChaiScript/) - 用于C++的易于使用的嵌入式脚本语言. [BSD] [website](http://chaiscript.com/)
* [Lua](http://www.lua.org/) - 用于配置文件和基本应用程序脚本的小型快速脚本引擎. [MIT]
* [luacxx](https://github.com/dafrito/luacxx) - 用于创建Lua绑定的C++ 11 API. [MIT]
* [SWIG](http://www.swig.org/) - 一个可以让你的C++代码链接到JavaScript，Perl，PHP，Python，Tcl和Ruby的包装器/接口生成器. [GPL/Output not licensed]
* [V7](https://github.com/cesanta/v7) - 嵌入式的JavaScript 引擎. [GPLv2]
* [V8](http://code.google.com/p/v8/) - 谷歌的快速JavaScript引擎，可以被嵌入到任何C++应用程序中. [BSD]

## 序列化

* [Cap'n Proto](http://kentonv.github.io/capnproto/) - 快速数据交换格式和RPC系统. [MIT]
* [cereal](https://github.com/USCiLab/cereal) - C++11 序列化库. [BSD]
* [FlatBuffers](https://github.com/google/flatbuffers) - 内存高效的序列化库. [Apache2]
* [MessagePack](https://github.com/msgpack/msgpack-c) - C/C++的高效二进制序列化库，例如 JSON. [Apache2] [website](http://msgpack.org/)
* [protobuf](http://code.google.com/p/protobuf/) - 协议缓冲，谷歌的数据交换格式. [BSD]
* [protobuf-c](https://github.com/protobuf-c/protobuf-c) - C语言的协议缓冲实现. [BSD]
* [SimpleBinaryEncoding](https://github.com/real-logic/simple-binary-encoding) - 用于低延迟应用程序的对二进制格式的应用程序信息的编码和解码. [Apache2]
* [Thrift](https://thrift.apache.org/) - 高效的跨语言IPC/RPC，用于C++，Java，Python，PHP，C#和其它多种语言中，最初由Twitter开发. [Apache2]

## 视频

* [libvpx](http://www.webmproject.org/code/) - VP8/VP9编码解码SDK. [BSD]
* [FFmpeg](https://www.ffmpeg.org/) - 一个完整的，跨平台的解决方案，用于记录，转换视频和音频流. [LGPLv2/GPL2]
* [libde265](https://github.com/strukturag/libde265) - 开放的h.265视频编解码器的实现. [LGPL] [website](http://www.libde265.org/)
* [OpenH264](https://github.com/cisco/openh264) - 开源H.364 编解码器. [BSD] [website](http://www.openh264.org/)
* [Theora](http://www.theora.org/) - 免费开源的视频压缩格式. [BSD]

## 虚拟机

* [CarpVM](https://github.com/tekknolagi/carp) - C中有趣的VM，让我们一起来看看这个. [GPLv3]
* [MicroPython](https://github.com/micropython/micropython) - 旨在实现单片机上Python3.x的实现. [MIT]
* [TinyVM](https://github.com/jakogut/tinyvm) - 用纯粹的ANSI C编写的小型，快速，轻量级的虚拟机. [MIT]

## Web应用框架

* [Civetweb](https://github.com/bel2125/civetweb) - 提供易于使用，强大的，C/C++嵌入式Web服务器，带有可选的CGI，SSL和Lua支持. [MIT]
* [CppCMS](http://cppcms.com/) - 免费高性能的Web开发框架(不是 CMS). [LGPLv3]
* [Crow](https://github.com/ipkn/crow) - 一个C++微型web框架(灵感来自于Python Flask). [BSD]
* [Kore](https://kore.io/) - 使用C语言开发的用于web应用程序的超快速和灵活的web服务器/框架. [ISC]
* [libOnion](http://www.coralbits.com/libonion/) - 轻量级的库，帮助你使用C编程语言创建web服务器. [LGPLv3]
* [QDjango](https://github.com/jlaine/qdjango/) - 使用C++编写的，基于Qt库的web框架，试图效仿Django API，因此得此名. [LGPL]
* [Wt](http://www.webtoolkit.eu/wt) - 开发Web应用的C++库. [GPL/Commercial]

## XML
*XML就是个垃圾，xml的解析很烦人，对于计算机它也是个灾难。这种糟糕的东西完全没有存在的理由了. -Linus Torvalds*

* [Expat](http://www.libexpat.org/) - 用C语言编写的xml解析库. [MIT]
* [Libxml2](http://xmlsoft.org/) - Gnome的xml C解析器和工具包. [MIT]
* [libxml++](http://libxmlplusplus.sourceforge.net/) - C++的xml解析器. [LGPLv2]
* [PugiXML](http://pugixml.org/) - 用于C++的，支持XPath的轻量级，简单快速的XML解析器. [MIT]
* [RapidXml](http://rapidxml.sourceforge.net/) - 试图创建最快速的XML解析器，同时保持易用性，可移植性和合理的W3C兼容性. [Boost]
* [TinyXML](http://sourceforge.net/projects/tinyxml/) - 简单小型的C++XML解析器，可以很容易地集成到其它项目中. [zlib]
* [TinyXML2](https://github.com/leethomason/tinyxml2) - 简单快速的C++CML解析器，可以很容易集成到其它项目中. [zlib]
* [TinyXML++](https://code.google.com/p/ticpp/) - TinyXML的一个全新的接口，使用了C++的许多许多优势，模板，异常和更好的异常处理. [MIT]
* [Xerces-C++](http://xerces.apache.org/xerces-c/) - 用可移植的C++的子集编写的XML验证解析器. [Apache2]

## 多项混杂
*一些有用的库或者工具，但是不适合上面的分类，或者还没有分类*

* [C++ Format](https://github.com/cppformat/cppformat) - C++的小型，安全和快速格式化库. [BSD]
* [casacore](https://code.google.com/p/casacore/) - 从aips++ 派生的一系列C++核心库. [LGPL]
* [cxx-prettyprint](https://github.com/louisdx/cxx-prettyprint) - 用于C++容器的打印库. [Boost]
* [DynaPDF](http://www.dynaforms.com/) - 易于使用的PDF生成库. [Commercial]
* [gcc-poison](https://github.com/leafsr/gcc-poison) - 帮助开发人员禁止应用程序中的不安全的C/C++函数的简单的头文件.
* [googlemock](http://code.google.com/p/googlemock/) - 编写和使用C++模拟类的库. [BSD]
* [HTTP Parser](https://github.com/joyent/http-parser) :star: - C的http请求/响应解析器. [MIT]
* [libcpuid](https://github.com/anrieff/libcpuid) - 用于x86 CPU检测盒特征提取的小型C库. [BSD]
* [libevil](https://github.com/avati/libevil) - 许可证管理器. [GPLv3]
* [libusb](http://www.libusb.org/) - 允许移动访问USB设备的通用USB库. [LGPLv2]
* [PCRE](http://pcre.org/) - 正则表达式C库，灵感来自于Perl中正则表达式的功能. [BSD]
* [Remote Call Framework](http://www.deltavsoft.com/) - C++的进程间通信框架. [GPLv2/Commercial]
* [Scintilla](http://scintilla.org/) - 开源的代码编辑控件. [MIT]
* [Serial Communication Library](https://github.com/wjwwood/serial) - C++语言编写的跨平台，串口库. [MIT]
* [SDS](https://github.com/antirez/sds) - C的简单动态字符串库. [BSD]
* [SLDR](https://github.com/cesanta/sldr) - 超轻的DNS解析器. [GPLv2/Commercial]
* [SLRE](https://github.com/cesanta/slre) - 超轻的正则表达式库. [GPLv2/Commercial]
* [Stage](https://github.com/rtv/Stage) - 移动机器人模拟器. [GPLv2]
* [VarTypes](https://code.google.com/p/vartypes/) - C++/Qt4功能丰富，面向对象的管理变量的框架. [LGPL]
* [ZBar](http://zbar.sourceforge.net/) - 条形码扫描器’库，可以扫描照片，图片和视频流中的条形码，并返回结果. [LGPLv2]
* [CppVerbalExpressions](https://github.com/VerbalExpressions/CppVerbalExpressions) - 易于使用的C++正则表达式. [MIT]
* [QtVerbalExpressions](https://github.com/VerbalExpressions/QtVerbalExpressions) - 基于C++ VerbalExpressions 库的Qt库. [MIT]
* [PHP-CPP](https://github.com/CopernicaMarketingSoftware/PHP-CPP) - 使用C++来构建PHP扩展的库. [Apache2] [website](http://www.php-cpp.com/)
* [Better String](http://bstring.sourceforge.net) - C的另一个字符串库，功能更丰富，但是没有缓冲溢出问题，还包含了一个C++包装器. [BSD, GPLv2]

# 软件
*用于创建开发环境的软件.*

## 编译器
*C/C++编译器列表*

* [Clang](http://clang.llvm.org/) - 由苹果公司开发的.
* [GCC](https://gcc.gnu.org/) - GNU编译器集合.
* [Intel C++ Compiler](https://software.intel.com/en-us/c-compilers) - 由英特尔公司开发.
* [LLVM](http://llvm.org/) - 模块化和可重用编译器和工具链技术的集合.
* [Microsoft Visual C++](http://msdn.microsoft.com/en-us/vstudio/hh386302.aspx) - MSVC，由微软公司开发.
* [Open WatCom](http://www.openwatcom.org/index.php/Main_Page) - Watcom，C，C++和Fortran交叉编译器和工具. [Sybase Open Watcom Public License]
* [TCC](http://bellard.org/tcc/) - 轻量级的C语言编译器. [LGPL]

## 在线编译器
*在线C/C++编译器列表*

* [codepad](http://codepad.org/) - 在线编译器/解释器，一个简单的协作工具.
* [CodeTwist](http://codetwist.com/) - 一个简单的在线编译器/解释器，你可以粘贴的C,C++或者Java代码，在线执行并查看结果.
* [coliru](http://coliru.stacked-crooked.com/) - 在线编译器/shell， 支持各种C++编译器.
* [Compiler Explorer](http://gcc.godbolt.org/) - 交互式编译器，可以进行汇编输出.
* [CompileOnline](http://www.compileonline.com/compile_cpp11_online.php) - Linux上在线编译和执行C++程序.
* [Ideone](http://ideone.com/) - 一个在线编译器和调试工具，允许你在线编译源代码并执行，支持60多种编程语言.

## 调试器
*C/C++调试器列表*

* [Comparison of debuggers](http://en.wikipedia.org/wiki/Comparison_of_debuggers) - 来自维基百科的调试器列表.
* [GDB](https://www.gnu.org/software/gdb) - GNU调试器.
* [Valgrind](http://valgrind.org/) - 内存调试，内存泄露检测，性能分析工具.
* [x64_dbg](http://x64dbg.com/) - 一个开源的调试器(x64/x32)在windows.

## 集成开发环境
*C/C++集成开发环境列表.*

* [AppCode](http://www.jetbrains.com/objc/) - 构建与JetBrains’ IntelliJ IDEA 平台上的用于Objective-C，C,C++，Java和Java开发的集成开发环境.
* [CLion](http://www.jetbrains.com/clion/) - 来自JetBrains的跨平台的C/C++的集成开发环境.
* [Code::Blocks](http://www.codeblocks.org/) - 免费C，C++和Fortran的集成开发环境.
* [CodeLite](http://codelite.org/) - 另一个跨平台的免费的C/C++集成开发环境. [GPLv2 with an exception for plugins]
* [Dev-C++](http://sourceforge.net/projects/orwelldevcpp/) - 可移植的C/C++/C++11集成开发环境.
* [Eclipse CDT](http://www.eclipse.org/cdt/) - 基于Eclipse平台的功能齐全的C和C++集成开发环境.
* [Geany](http://www.geany.org/) - 轻量级的快速，跨平台的集成开发环境. [GPL]
* [IBM VisualAge](http://www-03.ibm.com/software/products/en/visgen) - 来自IBM的家庭计算机集成开发环境.
* [Irony-mode](https://github.com/Sarcasm/irony-mode) - 由libclang驱动的用于Emacs的C/C++微模式.
* [KDevelop](https://www.kdevelop.org/) - 免费开源集成开发环境.
* [Microsoft Visual Studio](http://www.visualstudio.com/) - 微软的集成开发环境.
* [NetBeans](https://netbeans.org/) - 主要用于Java开发的的集成开发环境，也支持其他语言，尤其是PHP，C/C++和HTML5.
* [Qt Creator](http://qt-project.org/) :star: - 跨平台的C++，Javascript和QML集成开发环境，也是Qt SDK的一部分.
* [rtags](https://github.com/Andersbakken/rtags) - C/C++的客户端服务器索引，用于 跟基于clang的emacs的集成.
* [Xcode](https://developer.apple.com/xcode/) - 由苹果公司开发.
* [YouCompleteMe](https://valloric.github.io/YouCompleteMe/) - 一个用于Vim的根据你敲的代码快速模糊搜索并进行代码补全的引擎.

## 构建系统

* [Bear](https://github.com/rizsotto/Bear) - 用于为clang工具生成编译数据库的工具.
* [Biicode](https://www.biicode.com/) - 基于文件的简单依赖管理器.
* [CMake](http://www.cmake.org/) - 跨平台的免费开源软件用于管理软件使用独立编译的方法进行构建的过程. [BSD]
* [CPM](https://github.com/iauns/cpm) - 基于CMake和Git的C++包管理器.
* [FASTBuild](http://www.fastbuild.org/docs/home.html) - 高性能，开源的构建系统，支持高度可扩展性的编译，缓冲和网络分布.
* [Ninja](http://martine.github.io/ninja/) - 专注于速度的小型构建系统.
* [Scons](http://www.scons.org/) - 使用Python scipt 配置的软件构建工具.
* [tundra](https://github.com/deplinenoise/tundra) - 高性能的代码构建系统，甚至对于非常大型的软件项目，也能提供最好的增量构建次数.
* [tup](http://gittup.org/tup/) - 基于文件的构建系统，用于后台监控变化的文件.

## 静态代码分析
*提高质量，减少瑕疵的代码分析工具列表*

* [Cppcheck](http://cppcheck.sourceforge.net/) -静态C/C++代码分析工具. - [source](https://github.com/danmar/cppcheck)
* [include-what-you-use](https://code.google.com/p/include-what-you-use/) - 使用clang进行代码分析的工具，可以#include在C和C++文件中.
* [OCLint](http://oclint.org/) - 用于C，C++和Objective-C的静态源代码分析工具，用于提高质量，减少瑕疵. - [source](https://github.com/oclint/oclint)
* [Clang Static Analyzer](http://clang-analyzer.llvm.org/index.html) - 查找C，C++和Objective-C程序bug的源代码分析工具.
* [List of tools for static code analysis](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis#C.2FC.2B.2B) - 来自维基百科的静态代码分析工具列表.

# 资源
*Various resources, such as books, websites, and articles for improving your C++ development skills and knowledge.*

## API设计

* [Beautiful Native Libraries](http://lucumr.pocoo.org/2013/8/18/beautiful-native-libraries/)
* [Designing Qt-Style C++ APIs](http://doc.qt.digia.com/qq/qq13-apis.html)

## 文章
*Fantastic C/C++ related articles.*

* [CppCon 2014 Speaker Materials](https://github.com/CppCon/CppCon2014) - Speaker materials from CppCon 2014.
* [C++Now 2014 Presentations](https://github.com/boostcon/cppnow_presentations_2014) - Presentation materials presented at C++Now 2014.
* [C++Now 2013 Presentations](https://github.com/boostcon/cppnow_presentations_2013) - Presentation materials presented at C++Now 2013.
* [C++Now 2012 Presentations](https://github.com/boostcon/cppnow_presentations_2012) - Presentation materials presented at C++Now 2012.

## 图书
*Fantastic C/C++ related books.*

* [The C++ Annotations](http://cppannotations.sourceforge.net/annotations/html/) - An in-depth guide on C++, intended for people with a good knowledge of C who want to make the transition to C++.
* [Free C Books](https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md#c) - vhf/free-programming-books/C.
* [Free C++ Books](https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md#c-1) - vhf/free-programming-books/C++.
* [The Definitive C++ Book Guide and List](http://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list) - A collection of quality books and an approximate skill level.

## 代码风格

* [google-styleguide](http://code.google.com/p/google-styleguide/) - Style guides for Google-originated open-source projects.
* [Google C++ Style Guide](http://google-styleguide.googlecode.com/svn/trunk/cppguide.xml)
* [GNU Coding Standard](http://www.gnu.org/prep/standards/standards.html)

## 讨论

* [CppCon Talks](https://www.youtube.com/user/CppCon/videos) :star: - The C++ conference.
* [Quick game development with C++11/C++14](https://github.com/SuperV1234/cppcon2014) - CppCon 2014 talk by Vittorio Romeo.

## 视频
*Fantastic C/C++ related videos.*

* [Awesome C Programming Tutorials in Hi Def [HD]](https://www.youtube.com/playlist?list=PLCB9F975ECF01953C) - A collection of detailed C Programming Language Tutorials for Beginners and New Programmers.
* [C++](https://www.youtube.com/playlist?list=PL2F919ADECA5E39A6) - by VoidRealms.
* [C++ Qt Programming](https://www.youtube.com/playlist?list=PL2D1942A4688E9D63) - by VoidRealms.
* [C++ Programming Tutorials Playlist](https://www.youtube.com/playlist?list=PLAE85DE8440AA6B83) - TheNewBoston Official Buckys C++ Programming Tutorials Playlist.
* [C++ Programming Tutorials from thenewboston](https://www.youtube.com/playlist?list=PLF541C2C1F671AEF6) - These are all of thenewboston's C++ programming tutorials.
* [C++ GUI with Qt Playlist](https://www.youtube.com/playlist?list=PLD0D54219E5F2544D) - Official Playlist for thenewboston C++ GUI with Qt tutorials.
* [C Programming Tutorials](https://www.youtube.com/playlist?list=PL78280D6BE6F05D34) - All of TheNewBoston's C programming tutorials are right here.
* [Bo Qian's playlist](https://www.youtube.com/user/BoQianTheProgrammer/playlists) - Boost Library, C++ Standard Library, Modern C++, Advanced C++, Advanced STL, ...

## 站点
*有用的C/C++相关站点.*

* [Standard C++](http://isocpp.org/) :star: - 新闻, 状态以及C++标准的讨论.
* [CppCon](http://cppcon.org/) - C++会议.
* [C++ reference](http://cppreference.com/) - C++98, C++03, C++11, C++14引用.
* [cplusplus.com](http://www.cplusplus.com/) - C++资源.
* [Meeting C++](http://meetingcpp.com/)

## 博客
*有用的C/C++相关博客.*

* [Coding For Speed](http://codingforspeed.com/) - Coding For Speed DOT COM, Less Execution Time.
* [Eric Niebler](http://ericniebler.com/)
* [Sticky Bits](http://blog.feabhas.com/)
* [Paul Fultz II's Blog](http://pfultz2.com/blog/)

## 其它Awesome项目
*收集有用的代码各片段, ...*

* [algorithms](https://github.com/xtaci/algorithms) - C++算法与数据结构.
* [c-algorithms](https://github.com/fragglet/c-algorithms) - C算法库.
* [C/C++ Awesome Pack](https://github.com/junian/CppAwesomePack) - 一些C++代码.

# 其它Awesome列表
*Other amazingly awesome lists*

* [lists](https://github.com/jnv/lists) - List of (awesome) lists curated on GitHub.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of awesome awesomeness.
* [awesome](https://github.com/sindresorhus/awesome) - A curated list of awesome lists.
* [free-programming-books](https://github.com/vhf/free-programming-books) - List of Freely Available Programming Books.
* [papers-we-love](https://github.com/papers-we-love/papers-we-love) - Papers from the computer science community to read and discuss.
* [awesome-php](https://github.com/ziadoz/awesome-php) - Awesome PHP libraries, resources and shiny things.
* [awesome-python](https://github.com/vinta/awesome-python) - Awesome Python frameworks, libraries and software.
* [awesome-sysadmin](https://github.com/kahun/awesome-sysadmin) - Awesome open source sysadmin resources.
* [awesome-talks](https://github.com/JanVanRyswyck/awesome-talks) - A lot of screencasts, recordings of user group gatherings and conference talks.
* [github-cheat-sheet](https://github.com/tiimgreen/github-cheat-sheet) - A list of cool features of Git and GitHub.
* [ToolsOfTheTrade](https://github.com/cjbarber/ToolsOfTheTrade) - Tools of The Trade, from Hacker News.
* [cheatsheets.org](http://www.cheatsheets.org/) - The largest collection of reference cards for developers.
* [cheat-sheets.org](http://www.cheat-sheets.org/) - All cheat sheets, round-ups, quick reference cards, quick reference guides and quick reference sheets in one page.
* [thefreecountry.com](http://www.thefreecountry.com/) - A collection of free programming resources, free webmasters' resources, free security resources and free utilities.

#贡献
请看[CONTRIBUTING](https://github.com/fffaraz/awesome-cpp/blob/master/CONTRIBUTING.md) 获得详细信息.
