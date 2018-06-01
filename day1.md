日期:2018.5.4
学习时间:1.5小时
目标：整理HTML5新知识点
是否达成：部分完成，未完待续
flag：能完成66天的学习


HTML5新功能
1.简化的DOCTYPE的声明
HTML5中的DOCTYPE声明(对字母大小写不敏感)
<!DOCTYPE HTML>
2.简化的编码字符集
<meta chatset = "utf-8">

3.简化的样式表和脚本引入
<link href = "test.css" rel = "stylesheet">
<script src = "test.js"></scritpt>
去掉link和script标签里面的type属性 

4.新增的全局属性
a.contenteditable(true/false)
b.spellcheck (true/false)
c.draggable（true/false）
d.dropzone（属性如下，用来规定当元素被拖动时发生的动作！）
dropzone属性说明copy创建拖动元素的一个副本link将拖动元素移动到一个新的位置move创建拖动元素的链接
e. hidden   隐藏属性，默认为显示
<label>输入框隐藏：<input type = “text”  hidden></label>
<label>输入框显示：<input type = “text”></label>

5.文档元素语义化标签

 


a. header标签 ：用来定义一个文档结构的“页眉”。通常情况下，会和h1-h6标签和hgroup标签组合，表示一个内容块的标题，或者是包含一个搜索框、导航栏、logo等栏目；

b. hgroup标签 ：用来定义一个文档中标题组。即一个内容块包含主标题和多个副标题时，多个h1-h6标签可以放在hgroup标签里面；

c. nav标签：用来定义一个文档中的导航区域,通常只用于页面的主要导航，侧边栏导航不适用；

d. article标签：用来定义一个文档中自成一体的东西，比如，论坛的帖子、博客的文章或者用户的评论。通常article标签里面有header、footer等标签。也可以自己嵌套使用；

e. section标签：用来定义一个文档结构中的“章节”内容，section和article的区别：article定义的是一个文档的独立版块，是一个容器元素。而section定义的是一个文档中的组成部分，和父标签是从属关系。article和section之间允许相互嵌套；

f. aside标签：通常包含在article标签中作为主要内容的附属信息部分。因此，aside和article常常组合使用，用来作为页面或站点全局的附属信息部分。

h. footer标签 ：用来定义一个文档结构的“页眉”。通常用来表示文档的作者信息、相关链接，版权资料等；

i. Figure
用<figure>和<figcaption>来语义化地表示带标题的图片 
<figure> 
<img src=”path/to/image” alt=”About image” /> 
<figcaption> 
<p>This is an image of something interesting. </p> 
</figcaption> 
</figure> 

6.文本元素语义化标签
b  加粗
i  倾斜
u underline下划线
code  单行代码
pre 用来定义与格式化的文本。也就是说可以保留原有的空格和换行符，用途：显示长代码。多行代码
q 用来定义引用文本，标记的是一行文本
cite 用来定义引用文本  引用的是书籍杂志的标题
blockquote  用来标记长文本引用 
time



未完待续...






















