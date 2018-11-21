# DAM-gamehub
DAM course final project based on OSS


游戏开发过程中有许多资源需要存储和管理。该项目提供了一个基于本地数据库MySQL和阿里云OSS进行管理的方式，页面设计及功能参考GitHub。

支持内容管理及检索、资源下载、多人协作、权限控制、日志记录等功能。



<h1>配置运行方式</h1>

STEP 1: 在本地数据库（推荐MySQL）中执行gamehub.sql文件建表。

STEP 2: 修改sqlfunc.py中第9行与第12行的数据库连接信息，使之与本地数据库的用户名和密码一致。

STEP 3: 修改oss.py中阿里云的密钥为自己的密钥。

STEP 4: 确保稳定的网络连接（OSS连接需求）。

STEP 5: 运行route.py
