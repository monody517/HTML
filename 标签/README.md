# 段落标签
## section
章节，通常有h1~h6来分辨
## h1~h6
各级标题
## p
段落
## aside
旁支内容
## foot
页脚，通常用来声明版权

`<foot>&copy; 版权信息</foot>`
## header
页眉
## main
主要内容
## div
划分

# 属性
## class
允许CSS和JavaScript按照类选择器和DOM方法来选择该元素
## id
id在使用时不会报错，同时有许多的禁忌词，如果使用了这些词会使声明无效，所以不到万不得已不使用
## style
style是元素的属性，他的优先级比在CSS中要高，但是比JS的优先级低
## tabindex
tabindex表示使用tab键选择的顺序，0表示最后一个选择，-1表示不会被选择
## title
一般用于显示隐藏的内容
## contenteditable
将元素变为可编辑的

# 内容标签
## dl+dt+dd
dt代表要描述的东西，dd代表描述的内容
## pre
保留空格，回车，Tab
## hr
添加分割线
## br
强制换行(在已经换行的上一行加)
## em
强调
## quote blockquote
  应用    块级引用 