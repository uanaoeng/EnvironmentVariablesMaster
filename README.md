软件说明
========
系统自带的环境变量管理器在编辑环境变量时，变量值和变量名都显示在一行当中，很不方便（特别是编辑path变量时），所以写了这个工具。

使用这款软件添加或编辑变量时，为方便查看变量的内容，软件自动在每个以分号";"相隔的目录后面添加了换行符，保存时，自动删除变量中所有的换行符。

效果截图
========
![主界面](mainForm.png)
![变量编辑界面](subForm.png) 

软件下载
============
[变量大湿](\EnvironmentVariablesManager\bin\Release)

程序需要改进的地方
=================

1. 应该把软件使用到的所有的库打包在一起，这样就可以避免版本不够的用户使用不了；

2. 加载ListView时，应该对ListView进行排序；

3. 新增项后，应该对listView进行排序，使新增的项出现在其应该出现的位置，而不是出现在最后 一项；

4. 应在删除完一项后，自动定位下一项或上一项，如果该项不是第一项，就往前删，如果是第一项，就往后删除，当所有项都已经删除完成，将编辑按钮和删除按钮设置为不可选中；

5. 调整listView列的尺寸；

6. 让窗口大小可以调节；

7. 处理Alt + U/S/N/V的事件。

