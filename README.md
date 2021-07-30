# CPython-Compiler-Analyse

CPython3.8编译器分析

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
8. [CPython语法改动实验:“非”和“前缀++”](https://github.com/rm-rf-me/CPython-Compiler-Analyse/blob/main/%E5%85%AB%E3%80%81CPython%E8%AF%AD%E6%B3%95%E6%94%B9%E5%8A%A8%E5%AE%9E%E9%AA%8C%E5%A2%9E%E5%8A%A0%E2%80%9C%E9%9D%9E%E2%80%9D%E4%B8%8E%E2%80%9C%E5%89%8D%E7%BC%80%E8%87%AA%E5%A2%9E%E2%80%9D.pdf)（已完成）
9.  reference（未全部完成）



如有任何问题，欢迎提交issue。未经许可禁止转载。


<img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" />
本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">知识共享署名-非商业性使用-禁止演绎 4.0 国际许可协议</a>进行许可。
