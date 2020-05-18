# 复合查询

⼀个 bool 查询，是⼀个或者多个查询⼦句的组合
总共包括 4 种⼦句。其中 2 种会影响算分， 2 种不影响算分
相关性并不只是全⽂本检索的专利。也适⽤于 yes | no 的⼦句，匹配的⼦句越多，相关性评分越⾼。
如果多条查询⼦句被合并为⼀条复合查询语句 ，⽐如 bool 查询，则每个查询⼦句计算得出的评分会被合并到总的相关性评分中。
must 必须匹配。 贡献算分
should 选择性匹配。贡献算分
must_not (Filter Context) 查询字句，必须不能匹配
filter (Filter Context) 必须匹配，但是不贡献算分