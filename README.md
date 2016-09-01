﻿##工程说明
该文件记录百度云盘目录文件生成的说明文档和程序编写过程<br>
##版本说明
###【commit1】
分解目录单元格中的字符串，分解成字符串数组，从下表1开始为一级目录，以此类推，字符串数组的下标零和最后一个都是空字符串<br>
###【涉及VBA编程点】
(1)以为字符串中的某个字符为分割线，分割字符串，形成字符串数组
所用到的函数为Split(要分割的字符串，分割字符)函数，其中分割字符也
是字符串，可以包含一个或者多个字符。<br>
(2)定义字符串，定义字符串数组<br>
###【commit2】
实现将前面分离出来的各级目录显示在excel上，但是还存在这大量的重复目录<br>，比如说如果是三级目录，一级和二级目录存在这重复显示的问题。<br>下个版本将解决这个问题。<br>
###【涉及VBA编程点】
(1)循环结构（for/next）,分支结构(if/elseif/ end if)<br>
(2)字符串数组的长度：length = UBound(a) - LBound(a) + 1<br>
