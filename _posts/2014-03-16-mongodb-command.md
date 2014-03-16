---
layout: default
title: mongodb常用命令
---
<p>
--------------数据库命令-----------------------
</br>
show dbs 查看当前有哪些数据库 </br>
use mydb 切换到名为mydb的数据库 </br>
db	打印出当前所在的数据库名称 </br>
show collections 查看当前的collection</br>
help 帮助 </br>
</br>

--------------创建collection以及插入文档------------------------
</br>
创建一个文档：</br>
wyj = { name : "wuyajie" , age : "27" } </br>
创建一个名为testData的collection（collection会默认自动创建），插入文档：</br>
db.testData.insert(wyj)</br>
确认文档是否在collection中：</br>
db.testData.find()</br>

</br>

</p>
<p>{{ page.date | date_to_string }}</p>