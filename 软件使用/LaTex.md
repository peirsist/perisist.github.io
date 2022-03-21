# LaTex





- [latex中\begin{verbatim}以及\verb有什么用？_音程的博客-CSDN博客](https://blog.csdn.net/qq_43391414/article/details/115129492)
- [Latex 中的空格汇总_hysterisis的博客-CSDN博客](https://blog.csdn.net/hysterisis/article/details/114123131)
- [LaTeX省略号 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/104112163#:~:text=在LaTeX中，分别使用“\ldots”，“\cdots”，“\vdots”，“\ddots”实现各种省略号. 可以看出“\ldots”实现了居底部的省略号，“\cdots”实现了居中的省略号.,而命令“\dots”可以根据实际情况自动地改变省略号的位置. 在写作的过程中，要根据自己的实际情况灵活地使用这些省略号（感谢评论指出）.)
- [Latex报错Missing $ inserted.inserted text_个人博客-CSDN博客](https://blog.csdn.net/zhangpeterx/article/details/86032665)
- [Latex输入特殊字符#$%&{}_^-＜＞|\_执念斩长河-CSDN博客_latex怎么打&](https://blog.csdn.net/m0_37149062/article/details/108240050)
- [Latex中输入数学中的“属于” 符号_sclxf的专栏-CSDN博客_latex属于符号怎么打](https://blog.csdn.net/sclxf/article/details/5387630)
- [「LaTeX」LaTeX 中三种向量表示：粗体1，粗体2，箭头向量 - 哔哩哔哩 (bilibili.com)](https://www.bilibili.com/read/cv3599113/#:~:text=「LaTeX」LaTeX 中三种向量表示：粗体1，粗体2，箭头向量 学习 2019-09-14 20%3A45,--阅读 · --喜欢 · --评论)
- [LaTeX宏包学习笔记之tcolorbox - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/338377565)
- [Latex彩色框_金良山庄-CSDN博客_latex彩色盒子模板](https://blog.csdn.net/golden1314521/article/details/42871065)
- 







```latex
\begin{enumerate}[i)]
	\item...
	\item...
\end{enumerate}
```



```latex
\url{https://github.com/davidgao666/HedaBachelorTemplate}
```



```latex
\begin{description}
  \item[Step 1] ... 
  \item[Step 2] ...
  \item[Step 3] ...
\end{description}
```



# 插入公式

#### 插入多行公式时，空格问题

第一个正确，第二个不对，因此在插入公式时，就不要有空格，避免不必要的麻烦。

```latex
\begin{equation}
\left\{ \begin{array}{l}
	r_k=\sum_{j=1}^p{w_{kj}x_j\text{,}}\\
	v_k=r_k-\theta _k,\\
	y_k=\varPhi \left( v_k \right),\\
\end{array} \right.	
\end{equation}

```



```latex
\begin{equation}

\left\{ \begin{array}{l}
	r_k=\sum_{j=1}^p{w_{kj}x_j\text{,}}\\
	v_k=r_k-\theta _k,\\
	y_k=\varPhi \left( v_k \right),\\
\end{array} \right.

\end{equation
```





