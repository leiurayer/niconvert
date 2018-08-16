过滤器文件格式定义
==================

[文档目录](./README.md)

过滤器文件支持两种格式：

* 纯文本格式，以 `.txt` 为扩展名
* Pyhton 格式，以 `.py` 为扩展名

纯文本格式
----------

每行一条正则被表达式，例如：

```
最后
结局
^剧透
是凶手$
```

表达式使用部分匹配，简单的关键词直接打上即可。

如果要使用完全匹配，可以和 ``^`` 或 ``$`` 配搭使用。

具体参考 Python 的[正则文档][re]。

[re]: https://docs.python.org/3/library/re.html

Python 格式
-----------

TODO