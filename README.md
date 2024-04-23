# Misaka-Conference



## 编译

编译命令：

```
latexmk -bibtex -pdf Misaka.tex
```

pdflatex Misaka.tex 更新不了bib

用latexmk -xelatex会缺字体

用latexmk 图片会报错

编译：PDFLaTex ——>BibTex——>PDFLaTex——>PDFLaTex

用PDFLaTeX编译你的 .tex 文件 , 这是生成一个 .aux 的文件, 这告诉 BibTeX 将使用那些应用；
用BibTeX 编译 .bib 文件；
再次用PDFLaTeX 编译你的 .tex 文件，这个时候在文档中已经包含了参考文献，但此时引用的编号可能不正确；
最后用PDFLaTeX 编译你的 .tex 文件，如果一切顺利的话, 这是所有东西都已正常了。



## 大纲   Outline

Misaka: A Visualized Swarm Testbed for Smart Grid Algorithm Evaluation

介绍和背景 INTRODUCTION

- 

定位： an open-source open-hardware swarm interfaces for Smart Grid Algorithm.

a Visualized Testbed for Smart Grid Algorithm Evaluation



In this article, we present Misaka, a visualized swarm testbed for smart grid algorithm evaluation, also an extendable open-source open-hardware platform for developing tabletop tangible swarm interfaces.

The platform consists of a collection of custom-designed 3-onmi-wheeled robots each 10 cm in diameter, high accuracy localization through a microdot pattern overlaid on top of the activity sheets, and a software framework for application development and control, while remaining affordable (per unit cost about 30 USD at the prototype stage). We illustrate the potential of tabletop swarm user interfaces through a set of smart grid algorithm development application scenarios developed with Misaka.

In summary, our contributions are:

- The first open-source hardware/software platform for smart grid algorithm evaluation with tabletop swarm user interfaces
- Redefinition for Algorithm Visualization with several implemented examples
- A set of scenarios to illustrate the unprecedented possibilities offered by Misaka swarm and by tabletop swarm user interfaces in general
- A common platform for any algorithm visualization, and other interactive swarm user interfaces

Furthermore, as benefits, Misaka:

- are modular each unit, can be extended with powerful platform, such as NVIDIA Jetson NANO.
- can simulate real smart grid communication scenarios with Zigbee modular on board
- can interact with user moving and turning the robot or using the illuminated capacitive touch keys on the robot 
- can be manipulated either individually or collectively
- are small enough to also act as “pixels” of a physical display
- can coexist in large numbers
- are lightweight, can operate on any horizontal surface, and relatively cost-effective: about 30 USD each now, down to
$15 if mass manufactured.

测试算法解释 Test Algorithm

UI EXAMPLES WITH MISAKA : 

- 动态迭代过程
- 信息传输流（带小屏显示帧数据）
- 时间轴尺度操纵



软硬件架构 HARDWARE AND SOFTWARE DESIGN

LIMITATIONS AND FUTURE WORK

CONCLUSION



## 挂arXiv

# Endorsement needed for eess.SY

You must get an endorsement from another user to submit an article to category eess.SY (Systems and Control).

*arXiv is an openly accessible, moderated repository for scholarly articles in specific scientific disciplines. Material submitted to arXiv is expected to be of interest, relevance, and value to those disciplines. Endorsement is necessary but not sufficient to have a article accepted in arXiv. All submissions are subject to [moderation](https://arxiv.org/help/moderation) and arXiv reserves the right to reject or reclassify any submission.*

We've sent an email message to **ztl20@tsinghua.org.cn** with a unique *endorsement code*; please forward this e-mail to someone authorized to endorse you for category eess.SY (Systems and Control.)

**Who is qualified to endorse?**

To endorse another user to submit to the eess.SY (Systems and Control) subject class, an arXiv submitter must have submitted 3 papers to **any of eess.AS, eess.IV, eess.SP or eess.SY** earlier than three months ago and less than five years ago.

You can find out if a particular person is qualified to endorse by looking up one or more of their articles and clicking on the link "Which of the authors of this article can endorse?" at the bottom of the abstract.

It would be good for you to find an endorser who is connected with you: for instance, if you're a graduate student, your thesis advisor or another professor in your department would be a good choice. Otherwise, you should choose an endorser whose work is related to the subject of your article.

**Your unique endorsement code is: GGUBKT**