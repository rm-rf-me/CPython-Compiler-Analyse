# CPython-Compiler-Analyse

CPython3.8编译器分析
> 在之前的一段时间里，我做了一些关于CPython虚拟机分析和改动的工作。在查找相关资料的过程中发现，目前我所能找到的这个领域的中文资料还很少，尤其是没有一个成套的、足够细致而且易于理解的资料能够帮助我一下子入门并且明白我需要做什么。在这个过程中我走了许多弯路，查阅了大量资料，才初步的了解了CPython编译器的大概框架。所以我写这一系列博客的目的，就是想要做出一个能够把CPython编译器从头讲到尾，能让一个完全不了解CPython甚至不了解Python的人看明白CPython编译器的整个架构。算是补齐中文博客对这个领域的一点空白。

> 这个系列并没有按照目录顺序进行编写，整个系列的第一篇反倒是最后一篇：[CPython语法改动实验:“非”和“前缀自增”](./八、CPython语法改动实验增加“非”与“前缀自增”.pdf)（已完成）。我想写的东西很多而写的速度又很慢，所以我并不确定自己有没有毅力把这个系列写完。而不管我有没有写完，我都推荐每个读者去看一下最后一篇[reference.md](./MD/reference.md)，这里面包含了我认为很有用的资料，能够帮助你找到更多信息。


## 目录

0. Python环境配置、Makefile分析（未全部完成）
   1. Python环境配置：这里引用我之前的一篇文章：[Python环境搭建简易指南](https://github.com/rm-rf-me/Python-Setup-tutorial/blob/master/Python%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA%E7%AE%80%E6%98%93%E6%8C%87%E5%8D%97.pdf)。这篇文章站在深度学习的Python应用角度，目的是指导搭建一个可用的Python深度学习环境，包括虚拟环境、包管理器以及显卡环境等。所以其中的大部分内容超出了CPython编译器分析的范畴，但该博客覆盖了Windows、MacOS和Linux三个平台上Python环境搭建的绝大部分基础内容，所以Python环境配置部分引用这篇文章。
   2. CPython源码下载及Makefile分析（未完成）
1. CPython概述（未完成）
2. CPython词法分析（未完成）
3. CPython语法分析（未完成）
4. CPython中CST到AST和AST优化（未完成）
5. CPython符号表和CFG生成（未完成）
6. CPython字节码生成和窥孔优化（未完成）
7. CPython字节码执行（未完成）
8. [CPython语法改动实验:“非”和“前缀自增”](./八、CPython语法改动实验增加“非”与“前缀自增”.pdf)（已完成）
9.  [reference.md](./MD/reference.md)（正在更新）



如有任何问题，欢迎提交issue。未经许可禁止转载。

