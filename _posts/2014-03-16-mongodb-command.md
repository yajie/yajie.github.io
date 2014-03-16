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

<div>
注释：</br>
1、什么是文档？</br>
mongodb中的最基本的数据单元，类似于RDBMS中一个表的一条记录。</br>
</br>
2、什么是collection?	</br>
mongodb中的collection类似于RDBMS中的表，但是一个collection中的文档可以有不同的字段，一般来说，同一个collection中的文档之间应该有着强相关的关系。</br>
</div>

</br>

</p>
<p>{{ page.date | date_to_string }}</p>