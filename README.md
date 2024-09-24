# tools-collect
tools collect

## 1. TokenTest.zip    
用途：实现一个窃取令牌来权限提升的loader   
使用：TokenTest.exe beacon.exe（beacon.exe自行做免杀即可）   
原文链接：https://mp.weixin.qq.com/s/xvgzmtXfyanpWLlw7uQOzA   

## 2. todeskpass.zip，Todesk密码提取.zip，向日葵密码提取器.zip
用途：todesk/sunlogin最新版设备代码、连接密码读取   
版本：todesk官网最新版：4.7.4.8   
使用：   
tasklist /svc   
procdump64.exe -accepteula -ma 11652(实际的pid)   
todesk_pass.exe   
原文链接：https://mp.weixin.qq.com/s/SLIEg36LOJpJYgY6N-0dGg    

## 3. Exchange 信息收集工具
用途：Exchange信息收集工具    
Exchange利用：    
https://forum.butian.net/share/1837    
https://mp.weixin.qq.com/s/_1R22o94pykFJgphVLUgXg    
https://github.com/ffffffff0x/1earn/blob/master/1earn/Security/RedTeam/%E5%90%8E%E6%B8%97%E9%80%8F/%E5%AE%9E%E9%AA%8C/Exchange.md    
https://evi1cg.me/archives/Exchange_Hack.html    
原文链接：https://mp.weixin.qq.com/s/oUXAdl4CvDrX_9Rc6Ax1XQ    

## 4. chfs文件共享工具
用途：当我们在打攻防比赛中会遇到内网机器不出网的问题，这个时候往不出网的机器上上传文件就比较困难，chfs内网文件共享工具，仅需在命令行环境运行，即可生成小型的web服务器，方便命令行情况下下载文件，适用于内网大规模机器不出网的环境下，会给横向移动带来很大方便！    
工具地址：http://iscute.cn/chfs    
windows使用命令：chfs.exe --port=8081 -path C:\\    

