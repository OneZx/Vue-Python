> `virtualenvwrapper`的安装

- `pip install virtualenvwrapper-win` (不要在Scripts文件夹下运行)
- linux下`pip install virtualenvwrapper`
- workon 列出所有虚拟环境
- mkvirtualenv Vue-python 新建虚拟环境,默认目录在`C:\Users\xxx\Envs`下
- 修改`mkvirtualenv`的默认目录,新增环境变量`WORKON_HOME`

![](/assets/workon.png)

- deactivate 退出虚拟环境
- workon py3vue 进入虚拟环境

#### 更新pip版本
- 使用管理员权限运行cmd(不然可能没有权限更新)

- 运行`python -m pip install --upgrade pip`

- `pip -V` 检查版本

- 进入D盘  `d:`