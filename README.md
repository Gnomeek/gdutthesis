# gdutthesis
广东工业大学LaTeX论文项目模板(非官方)





# 与样张区别之处

1. 左边距

   按照手册要求`页边距:上边距:30mm;下边距:25mm;左边距:30mm;右边距:20mm;`，但是很显然在样张中左右两侧的边距是相同的，可见样张它自己都没有按照自己的要求严格执行。

2. 封面

   样张中个人信息那块东西，居然都没有居中。在此处我严格居中了。

3. 字间距

   样张中的英文摘要行间距与中文摘要行间距都不同。在此处设置为相同间距。行间距特地将LaTeX间距强行修正为了Word版的行间距。

4. 字体

   样张中`I级叶/盘转子错频方案的对比分析`中的`I`这个字符用的还是中文的黑体加粗，不符合手册要求。在本模板中为手册要求的英文字体用**Times New Roman**字体。

5. 目录

   样张中的目录缩进自己都没有对齐，这么丑真的看得下去吗。

   标题`目录`二字中间有四个空格，在本模板只用了两个，与摘要、致谢等保持一致。

   样张中的标题的段后距离太窄，与其他地方不一致。本模板与其他章标题段前后距离保持一致。

6. 公式

   样张中的公式没有居中，在本模板中居中了。

7. 图

   样张中图标题和子图标题之间的间距过大，在本模板中缩小了间距。

8. 条和款

   样张中他们的间距设置混乱，款间距比条还大。在本模板中都设置为1.5倍行距

# TODOLIST

- [ ] “节”、“条”的段前、段后各设为 0.5 行
- [ ] 

# 翻译

```
\boolfalse {citerequest}\boolfalse {citetracker}\boolfalse {pagetracker}\boolfalse {backtracker}\relax 
\defcounter {refsection}{0}\relax 
\contentsline {chapter}{一、外文参考文献翻译-原文}{1}{chapter.1}
\defcounter {refsection}{0}\relax 
\contentsline {chapter}{二、外文参考文献翻译-译文}{13}{chapter.1}
\defcounter {refsection}{0}\relax 
```
