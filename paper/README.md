# 论文

本页存放本人毕业设计《电力系统网源协调控制技术平台》论文。

本tex文件也可以作为模板使用，其格式根据2022年暨南大学本科毕业论文格式制定。



## 模板使用须知：

- 参考文献使用`\upcite{}`代替`\cite{}`
- 文章从`\section{}`开始，可自动编号的共有3级，即`\section{}`,`\subsection{}`,`\subsubsection{}`，若需要第四、五级，可以使用`\paragraph{}`和`\subparagraph{}`
- 使用`\paragraph{}`和`\subparagraph{}`，不会自动编号，需要手动进行编号。这里提供手动编号的一个方法：
  - 对于`\paragraph{}`，使用\thesubsubsection命令获取上一级的编号，并手动输入下一级编号，如`\paragraph{\thesubsubsection.1 标题}`
  - 对于`\subparagraph{}`，使用\thesubsubsection命令获取上一级的编号，并手动输入下两级编号，如`\subparagraph{\thesubsubsection.1.1 标题}`
- 编译顺序：xeTex -> BibTex -> xeTex -> xeTex -> pdf
- 代码环境默认高亮，常用语言中除了JavaScript以外都支持，全部语言请看官方文档
