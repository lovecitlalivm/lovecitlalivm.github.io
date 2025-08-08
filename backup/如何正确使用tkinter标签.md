#标签
##标签有什么用？
在tkinterGUI程序中创建标签可以实现
1.文字显示
2.图片显示
这使得标签变得非常实用
---
##如何创建文字标签？
在[上一篇博客](https://lovecitlalivm.github.io/post/ru-he-shi-yong-tkinter-chuang-jian-yi-ge-GUI.html"访问博客")中，我创建了一个600x600的GUI程序，代码如下
```
import tkinter as tk

master = tk.Tk()
master.geometry('600x600')
master.title('Hello tkinter')

master.mainloop()
```
那么要创建文字标签只需要这样
```
import tkinter as tk

master = tk.Tk()
master.geometry('600x600')
master.title('Hello tkinter')

label = tk.Label(master,text='祝你开心!')#等号前的只是标签的名字可以随意哦（英文）
label.place(x=50,y=100)#这里使用label.pack()同样可行,用place为准

master.mainloop()
```
效果如下
![图片加载失败](https://raw.githubusercontent.com/lovecitlalivm/lovecitlalivm.github.io/refs/heads/main/images/b2_1.png)
