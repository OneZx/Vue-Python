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
- mysql数据库默认InnoDB引擎,还有种是MyISAM
<http://blog.csdn.net/u013986386/article/details/52869648>