Shortest
========

Shortest is an database interface to store and manipulate short message.








Shortest开源项目
==

Shortest是一个用于操作短条目信息的数据库接口库。其具体特性暂时包括：

- 向数据库中存储类似微博信息的短条目；
- 可设定短条目的文本内容字符数限制，默认为140字；
- 使用列表（或称作空间）来归纳短条目。每个短条目可以从属于多个列表；
- 为每条短条目在所属某列表中指定一个唯一的固定顺序编号，可调整短条目的顺序编号；
- 通过列表来实现用户之间的共享与同步（类似于CatchNotes的共享空间）；

后续规划可支持短条目的内容中包含图片、二进制数据文件等。

计划支持的数据库包括：

- MongoDB
- GAE Datastore

项目地址

[GitHub 托管][1]
[Google Code托管][2]


  [1]: https://github.com/funfunsay/Shortest
  [2]: https://code.google.com/p/shortest/