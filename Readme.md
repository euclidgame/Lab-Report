# 实验报告

## 待做事项

封面太丑了，会改的会改的。

### Overview

总揽部分的软件部分需要补充。

### Software

整个软件部分的介绍。这一部分会有一些插图，放到`graphics`目录下，链接到figuretable。



## 一些预设

基本需要的预设都设置好了，例如一些新设置的命令在`preamble/general.tex`中定义，关于代码块的风格在`preamble/lstcustom.sty`中定义。一些命令的作用以及代码块的风格可以自行修改（我努力了）。现在的代码块只提供了`verilog`和`java`，因为我有用到，如果需要`mips`汇编可以添加。

常用的命令

```latex
\chapter{Software}
\code{} //努力打造类似markdown的伪代码块（bushi
\lstinline$xxx$ //没有颜色的行间代码
\coloremph{} // 以一种奇怪的颜色来强调
\file{} //还是奇怪的颜色，用于文件名
\begin{lstlisting}[style = xxx, caption = xxx]
\end{lstlisting} //罗列代码

//直接包含代码文件
An example that includes a \texttt{.java} file is shown in listing \ref{lst:file}.

\lstinputlisting[caption={A listing from the file
  \texttt{xxx.java}}, label={lst:file}]{xxx.java}
```

一些字体可能后来会有修改，不过我感觉对于中文来说，宋体和楷体足够用了。