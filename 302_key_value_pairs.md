键值对
======
WiredTiger文件的底层是键值存储，即文件中的条目是成对的键和值。这些键和值可以被直接访问，文件游标只能从单个文件中返回数据，而不能引用其它相关的文件或数据。例如，如果索引丢失了或者与主数据不一致了，文件游标能从索引中读取而不出错（即使返回的一些键在主数据中不存在）。

在行存文件中，键和值都是变长字节的字符串，长达（4GB-512B）。

在列存文件中，键是64位的记录号，文件中的第一个记录号是1。值也是变长字节的字符串，长达（4GB-512B），或者是位域，每个位域1到8位。
