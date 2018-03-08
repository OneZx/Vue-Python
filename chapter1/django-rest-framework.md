**安装Django REST framework**

- [django restful](http://www.django-rest-framework.org/)

```
pip install djangorestframework
pip install markdown       # Markdown support for the browsable API.
pip install django-filter  # Filtering support
```

- pip list 列出安装的包
- pip install django

```
(py3vue) C:\Users\99602>pip install django
Collecting django
  Downloading Django-2.0.3-py3-none-any.whl (7.1MB)
    0% |                                | 10kB 1.9kB/s eta 1:03:51Exception:
Traceback (most recent call last):
  File "e:\learning-python\virtualenv\py3vue\lib\site-packages\pip\_vendor\requests\packages\urllib3\response.py", line 232, in _error_catcher
    yield
  File "e:\learning-python\virtualenv\py3vue\lib\site-packages\pip\_vendor\requests\packages\urllib3\response.py", line 314, in read
    data = self._fp.read(amt)
  File "e:\learning-python\virtualenv\py3vue\lib\site-packages\pip\_vendor\cachecontrol\filewrapper.py", line 60, in read
    data = self.__fp.read(amt)
  File "d:\server\python3.6\Lib\http\client.py", line 449, in read
    n = self.readinto(b)
```
> 安装django2.0出错,于是在pycharm中新建django项目自动安装

- `cd /d e:/` 进入e盘(我的django项目新建在e盘)
- `cd E:\Vue-Python\py3vue\venv\Scripts` cd到scripts中
- `activate.bat` 运行,进入新建项目的虚拟环境中
- 在这里重新装 `django-rest-framework  markdown`等各种
- `pip install markdown`也可能出错 可能是网络问题

> 使用豆瓣源

- `pip install xxx -i http://pypi.douban.com/simple/ `

- 安装完所有的后(warning不用管)

![](/assets/piplist.png)

