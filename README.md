# Awesome-Binaries

## 目录

- [AEG](#AEG)
- [CGC](#CGC)
- [ShellPhish](#ShellPhish)
- [Mechanical Phish](#cechanical-phish)
- [Tools](#Tools)
- [Awesome Blogs (Article)](#awesome-blogs-(article))

## 置顶
整理近期工作，梳理相关资源，辅助后续工作开展。(持续更新)

## AEG
- [《AEG: Automatic Exploit Generation》](https://github.com/maskhed/MyPapers/blob/master/AEG_Automatic_Exploit_Generation.pdf)  
CMU 2011 年发表的 AEG 综述性文章
- [《(State of) The Art of War: Offensive Techniques in Binary Analysis》](https://github.com/maskhed/MyPapers/blob/master/2016_SP_angrSoK.pdf)  
2016 年 UCSB 发表于 S&P 的论文，涉及 AEG 与 Angr 架构
- [《Survey of Automated Vulnerability Detection and Exploit Generation Techniques in Cyber Reasoning Systems》](https://github.com/maskhed/MyPapers/blob/master/Survey%20of%20Automated%20Vulnerability%20Detection%20and%20Exploit%20Generation%20Techniques%20in%20Cyber%20Reasoning%20Systems.pdf)  
    介绍了 AEG、CGC相关情况，重点分析了 CGC 竞赛中的 Mayhem、Mechaphish 两套 CRS 系统。


## CGC
- [DARPA CGC](https://github.com/CyberGrandChallenge) -  CGC organization on Github.
- [CGC-Corpus](http://www.lungetech.com/cgc-corpus/) - This site documents the data gathered from the CGC qualifiers and the Final event.
- [Cyber Grand Challenge 简介](https://ma3k4h3d.top/2018/11/01/CGC/) - 简要介绍 CGC 背景、赛制、参赛团队情况。

## ShellPhish
传统 CTF 强队，由加利福尼亚大学圣芭芭拉分校学生组成，指导教授 Christopher Kruegel。[首页](http://shellphish.net)、[Github Organization](https://github.com/shellphish)。
- [CGC Shellphish](http://shellphish.net/cgc/) - Shellphish 参加 CGC 竞赛的官方页面。

    ### 1）Driller 
     在AFL的基础上添加动态符号执行引擎的crash模糊测试工具。 
    - [《Driller: Augmenting Fuzzing Through Selective Symbolic Execution》](https://github.com/maskhed/MyPapers/blob/master/2016_NDSS_Driller.pdf) - 2016 年发表于 NDSS 的论文
    - [Driller Github](https://github.com/shellphish/driller) - Driller 源码，基于论文原理实现   
    - [Driller安装](https://blog.csdn.net/xiaosatianyu/article/details/60874004) - 作者总结了Driller安装过程
    - [Driller分析](https://blog.csdn.net/Chen_zju/article/details/80791281) - 作者对关键代码进行了分析
    
    ### 2）Shellphish-afl
    A pip wrapper around AFL. [Source Code](https://github.com/shellphish/shellphish-afl).  安装过程中若存在问题，需多参考 [issues](https://github.com/shellphish/shellphish-afl/issues)。
    
    ### 3）Fuzzer
    This module provides a Python wrapper for interacting with AFL. It supports starting an AFL instance, adding slave workers, injecting and retrieving testcases, and checking various performance metrics. Shellphish used it in Mechanical Phish to interact with AFL. [Source Code](https://github.com/shellphish/fuzzer)
    
    
    ### 4）Rex
    Shellphish's automated exploitation engine, originally created for the Cyber Grand Challenge. [Source Code](https://github.com/shellphish/rex)、[Installation Guide](https://github.com/shellphish/rex/issues/5).

## Mechanical Phish
- [Mechaphish](https://github.com/mechaphish) - Shellphish 为参加 CGC 而开发的 CRS(Cyber Reasoning System).
- [Mechaphish 文档](https://github.com/mechaphish/mecha-docs/blob/master/development.md) - Mechaphish 相关文档。
- [Mechaphish Docker](https://hub.docker.com/r/shellphish/mechaphish/) - Dockerhub 上提供的 Mechaphish 镜像。

## Tools
- [angr.io](https://angr.io)、[Angr Github](https://github.com/angr) - The angr project is the next-generation binary analysis framework created by the computer security lab at UC Santa Barbara!
- [AFL](http://lcamtuf.coredump.cx/afl/) - American fuzzy lop is a security-oriented fuzzer that employs a novel type of compile-time instrumentation and genetic algorithms to automatically discover clean, interesting test cases that trigger new internal states in the targeted binary. 
- [Radare2](https://www.radare.org/r/)、[Source Code](https://github.com/radare/radare2) - unix-like reverse engineering framework and commandline tools security.
- [BitBlaze](http://bitblaze.cs.berkeley.edu)、[Paper](http://bitblaze.cs.berkeley.edu/papers/bitblaze_iciss08.pdf) - Binary Analysis for Computer Security by UC Berkeley.


## Awesome Blogs (Article)  
- [AEGG - Automatic Exploit GG](http://ysc21.github.io/blog/2016-06-21-aegg.html) - YSc 撰写的关于 AEG 的文章
- [Dafeng's Blog](https://stfpeak.github.io) - 一生想做浪漫极客
- [Symbolic Execution Tramples CTF Challenge](https://p16.praetorian.com/blog/internetwache-re60-writeup-symbolic-execution-tramples-ctf-challenge)  
![](https://p16.praetorian.com/images/blog/posts/ctf/1_for_loop.png)
- [符号执行入门](https://blog.csdn.net/omnispace/article/details/80248252) - 介绍关于符号执行的基本概念，文中提及的论文及参考文献，可对后续深入学习提供路线。
- [Offensive Techniques in Binary Analysis](https://blog.csdn.net/doudoudouzoule/article/details/79197203) - 对 《(State of) The Art of War: Offensive Techniques in Binary Analysis》的翻译，可供参考。
- [小试shellphish开源的driller](https://www.trueai.cn/archives/395.html) 
- [wcventure](https://wcventure.github.io) - Cheng Wen is a Ph.D. student at the College of Computer Science and Software engineering in Shenzhen University since 2019. His research is in the area of program analysis, software verification, machine learning, cyber security, software testing, and formal method. 






