************************
此程序适用于对Windows系统启动后对系统内外网IP、启动时间进行上报，通过邮件的方式发送给指定邮箱
************************
v0.1<br>
基础的内外网IP读取并通过邮件上报
************************
v0.2<br>
更换外网IP查询接口，新接口新增IP对应实际地址
************************
v0.3<br>
新增查询系统启动时间函数，便于收件人判断，系统是否异常重启或脚本异常运行
************************
v0.4<br>
新增查询程序启动时间函数，便于收件人判断程序实际运行时间。
************************
v1.0<br>
配置完成版本
************************
v1.1<br>
新增使用配置文件配置邮件服务功能，若因配置文件引起程序错误，请删除根目录下的config.txt，并重新配置邮件服务
************************
<br>
exe文件在dist文件夹中，适用于未安装Python的运行环境，使用pyinstaller生成
<br>

邮件发送配置方式，请自行查询各邮箱开启SMTP教程
