### LiqunKit 综合漏洞利用工具



本程序由 Liqun @ snowlovely 共同驱动

仅限于内部测试使用，请勿用于未授权的攻击！！ 

该程序及用于安全人员本地测试使用！！

用户滥用造成的一切后果与作者无关！
！ 
使用者请务必遵守当地法律！！ 

本程序不得用于商业用途，仅限学习交流！！


--------------------------------------------------------------------------------------------------------------------------------------------------------------------

2021.11.03:「+」

1.新增通达OA漏洞利用模块

任意用户登陆获取Cookie

sql注入获取Cookie

后台文件包含getshell

后台任意文件上传

任意文件删除组合getshell

2.新增Shiro 550 漏洞利用模块


优化key检测机制

实现CBC/GCM 加密方式的秘钥检测

实现一键写入webshell到网站目录

实现一键写入文件到自定义目录

实现Linux一键反弹shell

-- 关于内存🐴

由于写好的程序在进行混淆加密后会导致部分内存🐴功能失效

所以先取消内存🐴功能后续与小伙伴有时间了在进行增加

3.对部分功能进行修复与重构


修复几个Weblogic Exp的兼容性
修复部分OA利用逻辑提高成功率
修复分块传输出现乱码的BUG


通达OA 模块
![image](https://user-images.githubusercontent.com/89302066/140003518-78acba31-7a12-498c-9577-f4ef07950b8d.png)

Shiro 模块
![image](https://user-images.githubusercontent.com/89302066/140003643-26e08567-b65a-4113-be9a-e998a38b0b5e.png)
![image](https://user-images.githubusercontent.com/89302066/140003726-f247c50d-3c04-444e-ae80-c50fdefa8d68.png)



--------------------------------------------------------------------------------------------------------------------------------------------------------------------

2021.09.06:「+」增加thinkPHP利用模块,增加万户OA controller上传exp
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

2021.08.15:「+」实验性新增 分块传输 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

2021.08.10:「+」Struts2  漏洞利用模块
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

2021.07.29:「+」Weblogic 漏洞利用模块
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

2021.07.20:「+」各类OA    漏洞利用模块
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

分块传输模块参考：
http://github.com/c0ny1/chunked-coding-converter
通达OA模块参考：
https://github.com/xinyu2428/TDOA_RCE
Shiro利用模块参考：
https://github.com/feihong-cs/ShiroExploit-Deprecated
https://github.com/j1anFen/shiro_attack
                



