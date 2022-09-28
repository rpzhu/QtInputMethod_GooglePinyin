# Qt 拼音输入法，采用Google拼音内核

## 文件夹说明

* googlepinyin<br>
Google拼音核心源码<br>

* plugin<br>
输入法插件源码<br>

* demo<br>
测试例子

## 编译说明
* 打开工程，直接编译，编译完成后把插件放在自己的工程中即可<br>
使用everyone 搜索dict ，找到qt 例子中的dict， 拷贝到 可执行文件目录下。 运行才能跑 中文输入法。

* 注意：plugin依赖googlepinyin工程，如果单独编译，先编译googlepinyin再编译plugin<br>
