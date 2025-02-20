# Paper Translation 本科毕业设计（论文）外文翻译

**请尽可能使用最新版本进行文章撰写，我们的代码仓库是：https://github.com/BITNP/BIThesis 。**

此文件夹中包含了北京理工大学本科生毕业设计（论文）外文翻译的全部内容，有关模板的使用方法更为详细的介绍，请参考：[bithesis 使用手册](./bithesis.pdf)。

## 特性

- 符合学校对毕业论文的要求。
- 内容和样式分离，所有的配置可以集中管理。
- 自适应的封面信息下划线长度。
- 由社区驱动，在积极地吸纳新功能、修复现有问题。

## 项目结构

```sh
.
├── README.md # 相关信息
├── bithesis.pdf # bithesis 使用手册
├── chapters
│   ├── 0_abstract.tex
│   └── 1_chapter1.tex
├── images
│   ├── bit_logo.png
│   └── header.png
├── main.pdf
├── main.tex
└── misc
    ├── 0_cover.tex
    ├── 2_toc.tex
    ├── 3_conclusion.tex
    ├── 4_reference.tex
    ├── 5_appendix.tex
    ├── 6_acknowledgements.tex
    └── ref.bib
```

## 编译方式

方式一（推荐）：
```
latexmk
```

方式二：
```
-> xelatex
-> biber
-> xelatex
-> xelatex
```

- *不推荐使用 pdflatex 进行编译*

## 其他链接

- 项目地址：https://github.com/BITNP/BIThesis
- Bug Report 与 Feature Request：https://github.com/BITNP/BIThesis/issues
- QQ 交流群：737548118

## 排版参考

- 《北京理工大学本科生毕业设计（论文）书写规范及打印装订要求》
- 《北京理工大学本科生毕业设计（论文）模板》
- 《外文翻译-封面》
