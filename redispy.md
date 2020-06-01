# redis-py 的安装

对于 Redis 来说，我们要使用 redis-py 库来与其交互，本节我们来介绍一下 redis-py 的安装方法。

## 相关链接

* GitHub：[https://github.com/andymccurdy/redis-py](https://github.com/andymccurdy/redis-py)
* 官方文档：[https://redis-py.readthedocs.io/](https://redis-py.readthedocs.io/)

## 安装方法

### pip 安装

推荐使用 pip3 安装，命令如下：

```
pip3 install redis
```

运行完毕之后即可完成 redis-py 的安装。

## 验证安装


为了验证库是否已经安装成功，可以在命令行下测试一下：

```python
$ python3
>>> import redis
>>> redis.VERSION
(2, 10, 5)
>>> 
```

在命令行首先输入 python3，进入命令行模式，输入如上内容，如果成功输出了其版本内容，那么证明 redis-py 成功安装，在后文我们会详细介绍 redis-py 的使用方法。

