
项目简介

项目结构

Flask程序的基本结构如下：

    │Project
    ├── README.md
    ├── app
    │   ├── __init__.py
    │   ├── api
    │   ├── auth
    │   ├── decorators.py
    │   ├── main
    │   │   ├── __init__.py
    │   │   ├── errors.py
    │   │   ├── forms.py
    │   │   └── views.py
    │   ├── models.py
    │   ├── static
    │   └── templates
    ├── config.py
    ├── manage.py
    ├── migrations
    ├── tests
    ├── prod
    ├── requirements
    └── utils

顶级文件夹：

- Flask程序一般都保存在名为app的包中；
- migrations文件夹包含数据库迁移脚本；
- 单元测试编写在tests包中；
- prod文件夹包含生产环境部署配置文件；
- utils包中放置工具函数或者可独立使用的库；
- requirements文件夹包含所有依赖包（不同环境），用来生成虚拟环境。

一些文件：

- config.py存储配置；
- manage.py用于指定flask命令的运行的程序和其他任务命令；
- README.md项目介绍。

运行

创建虚拟环境，安装运行所需要的包，使用git checkout 14a 命令，在终端

进入虚拟环境后，执行 source .flaskenv 命令，在执行flask run 
