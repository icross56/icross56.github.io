1. 斜体和粗体
使用 * 和 ** 表示斜体和粗体。（注意*号前需要有空格）

这是 *斜体*，这是 **粗体**。
示例：

这是 斜体，这是 粗体。

2. 分级标题
使用 === 表示一级标题，使用 --- 表示二级标题。

示例：

这是一个一级标题
============================

这是一个二级标题
--------------------------------------------------

### 这是一个三级标题
你也可以选择在行首加井号表示不同级别的标题 (H1-H6)，例如：# H1, ## H2, ### H3，#### H4。

3. 外链接
使用 [描述](链接地址) 为文字增加外链接。

示例：

这是去往 本人博客1 的链接。

4. 图片
你可以直接往编辑框中拖拽/粘贴一张图片。或者直接粘贴图片的地址链接。也可以使用 Markdown 语法 ![描述](图片链接地址) 插入图像。

例如下面三行行代码的效果是一样的：

https://dn-coderq.qbox.me/uploads/default/40/26474e6e754357a3.jpg
<img src="https://dn-coderq.qbox.me/uploads/default/40/26474e6e754357a3.jpg" />
![](https://dn-coderq.qbox.me/uploads/default/40/26474e6e754357a3.jpg)
示例：



5. 无序列表
使用 *，+，- 表示无序列表。

示例：

无序列表项 一
无序列表项 二
无序列表项 三
6. 有序列表
使用数字和点表示有序列表。点后有空格。

示例：

有序列表项 一
有序列表项 二
有序列表项 三
7. 文字引用
使用 > 表示文字引用。

示例：

野火烧不尽，春风吹又生。
8. 行内代码块
使用 `代码` 表示行内代码块。

示例：

让我们聊聊 html。

9. 代码块
使用 四个缩进空格 表示代码块。

示例：

这是一个代码块，此行左侧有四个不可见的空格。
10. 删除线
使用 <del>文本</del> 表示删除线。

这是一段错误的文本。

11. 键盘按钮
使用<kbd>Ctrl</kbd>表示一个 Ctrl 键盘按钮。

12. 加强的代码块
支持四十一种编程语言的语法高亮的显示，行号显示。

非代码示例：

$ sudo apt-get install vim-gnome
Python 示例：

@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None

class SomeClass:
    pass

>>> message = '''interpreter
... prompt'''
JavaScript 示例：

/**
* nth element in the fibonacci series.
* @param n >= 0
* @return the nth element, >= 0.
*/
function fib(n) {
  var a = 1, b = 1;
  var tmp;
  while (--n >= 0) {
    tmp = a;
    a += b;
    b = tmp;
  }
  return a;
}

document.write(fib(10));
13. 不支持的语法
在码农圈有些语法并不支持，比如：

不支持表格，包括markdown和使用<table>的语法
<iframe> 标签