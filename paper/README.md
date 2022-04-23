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

## BibTex样式：

除了官方支持的样式之外，本页[bst](https://github.com/ID-VerNe/jnuthesis/blob/main/paper/gbt7714-numerical.bst)文件中还加入了其他支持

- 标准[S]：
  - 引用方式：`otherarticalStandard`
  - 需要参数：`title`，`author`，`year`，`publisher`
  - 示例：
  
    ```latex
    @otherarticalStandard{20132013水轮机调节系统并网运行技术导则,
    	title={水轮机调节系统并网运行技术导则：DL/T 1245-2013},
    	author={电力行业水电站自动化标准化技术委员会},
    	year={2013},
    	publisher={北京：中国电力出版社}
    }
    ```
- 政府文件[Z]：
  - 引用方式：`otherarticalGOVDOC`
  - 需要参数：`title`，`author`，`year`
  - 示例：
  
    ```latex
    @otherarticalGOVDOC{电力并网运行管理规定,
	    title={电力并网运行管理规定},
    	author={国家能源局},
    	year={2021-12-21}
     }
    ```

