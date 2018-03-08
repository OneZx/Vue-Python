> settings.py中

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'py3vue',
        'USER': 'root',
        'PASSWORD': 'root',
        'HOST':'127.0.0.1',
        # 这句一会儿会抛出异常 要改
        'OPTIONS':{'init_command':'SET storage_engine=INNODB'},
    }
}
```
- Mysql数据库默认`InnoDB`引擎(mysql5.7),还有种是`MyISAM`
<http://blog.csdn.net/u013986386/article/details/52869648>

- [天涯教程](https://www.jianshu.com/p/da847259c7e3)

#### 新建数据库navicat
- 在navicat中,注意字符集和排序规则的选项

![](/assets/database.png)
