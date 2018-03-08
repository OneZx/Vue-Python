> settings.py中

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'py3vue',
        'USER': 'root',
        'PASSWORD': 'root',
        'HOST':'127.0.0.1',
        'OPTIONS':{'init_command':'SET storage_engine=INNODB'},
    }
}
```