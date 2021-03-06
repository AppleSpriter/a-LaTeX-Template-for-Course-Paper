# 机器学习实习LaTeX模板

## 具体格式要求

* 标题
	* 中文题目	2号黑体(22磅)
	* 英文题目	2号Times New Roman(22磅)
	* 作者		学号·专业班级·姓名，3号仿宋(16磅)
* 内容
	* 一级标题	4号黑体(LARGE)
	* 二级标题	5号黑体(large)
	* 三级标题	5号宋体(small)
	* 正文	5号宋体(9磅)

## 说明
* 代码插入在3.1节，建议使用lstlisting包插入代码，如果使用minted包编译排版代码，需要在编译选项中加入-shell-escape命令，并在python中安装pymentize库方可正常编译，具体配置可参照[这里](https://www.latexstudio.net/archives/328.html)
* TeXstudio中编译选项位置，选项-设置TeXstudio-命令-(根据编译器加入自定义命令) 或 选项-设置TeXstudio-构建-用户命令-键入自定义命令-修改默认编译器为自定义命令
* 公式、算法、表格、图片插图在3.2节，其中图片需要放在figs/ 中
* 参考文献在bib/ 中，通过cite{}命令引用
* 可能用到的预定义，theorem/lemma/proof 定理/引理/证明，使用\begin命令定义，标题全部改为中文
* \section \subsection标题分别为第X章/第X节
