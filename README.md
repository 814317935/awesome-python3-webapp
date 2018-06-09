# 根据廖雪峰py教程制作web blog.  
## 第一天  
### 搭建开发环境：  
确认系统安装的Python版本是3.6.x：  
	
	$ python --version Python 3.6.3 :: Anaconda custom (32-bit)  

异步框架aiohttp(2.1.0)：  
	
	$ pip3 install aiohttp  

前端模板引擎jinja2(2.9.6)：  
	
	$ pip3 install jinja2  

安装MySQL8.0：https://dev.mysql.com/doc/refman/8.0/en/installing.html   
MySQL的Python异步驱动程序aiomysql(0.0.9)：   

	$ pip3 install aiomysql  

###项目结构：  
awesome-python3-webapp/ <-- 根目录   
| +- backup/ <-- 备份目录   
| +- conf/ <-- 配置文件   
| +- dist/ <-- 打包目录   
| +- www/ <-- Web目录，存放.py文件   
| | | +- static/ <-- 存放静态文件   
| | | +- templates/ <-- 存放模板文件   
| +- ios/ <-- 存放iOS App工程   
| +- LICENSE <-- 代码LICENSE   

创建git仓库，并同步到GitHub(无法上传空文件夹)  