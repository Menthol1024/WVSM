# WVSM(WEB漏洞扫描管理平台) 写完功能介绍后上传代码
![image](https://user-images.githubusercontent.com/34536372/114827807-b9884600-9dfb-11eb-96df-801d38aa490f.png)
![image](https://user-images.githubusercontent.com/34536372/114828205-34e9f780-9dfc-11eb-8ee4-a9e41b61b4b5.png)
![image](https://img.shields.io/github/stars/Menthol1024/WVSM)
![image](https://img.shields.io/github/v/release/Menthol1024/WVSM?label=wvcm&style=flat-square)
## 一、平台简介
* 目前都有什么功能 ？
```
1. 可以对项目进行越权测试，需要两个不同权限的用户;
2. 可以对项目对应的IP进行端口测试;
3. 支持对探测到的端口进行简单的漏洞扫描;
4. 支持对项目IP对应的端口信息以及端口漏洞信息一键导出;
5. 支持人工排查越权漏洞，增加了手工对漏洞是否为误报进行设置;
6. 支持一键导出项目所有存在越权的URL信息;
7. 支持对项目的某些接口做白名单设置;
```
* 目前支持检测哪些漏洞 ？
```
1. fastjson 反序列化RCE
2. shiro 反序列化RCE
3. weblogic 反序列化RCE
4. redis 未授权漏洞
5. ZooKeeper未授权访问
6. Tomcat Ajp 文件读取漏洞
7. elasticsearch未授权访问漏洞
8. Docker Remote API 未授权访问漏洞
9. CVE-2019-7238 Nexus Repository Manager RCE
```
还有一些需要后期进行整合

* 附加实用工具
```
1. 密文类型判断功能

```
## 二、功能界面预览

* 管理台主界面

![image](https://user-images.githubusercontent.com/34536372/114825497-e25b0c00-9df8-11eb-9312-2b1a79a1b753.png)

* 新增任务界面

![image](https://user-images.githubusercontent.com/34536372/114832637-484b9180-9e01-11eb-9441-942d5297c7b0.png)

* 任务列表界面

![image](https://user-images.githubusercontent.com/34536372/114833386-1ab31800-9e02-11eb-90cd-82d6cd4232e4.png)

* 越权扫描任务详情界面

![image](https://user-images.githubusercontent.com/34536372/114833745-7c738200-9e02-11eb-8c29-d88fcecb7cec.png)

* 端口扫描任务详情界面

![image](https://user-images.githubusercontent.com/34536372/114833884-9d3bd780-9e02-11eb-879f-3145915d42ab.png)

* 项目端口扫描结果展示界面

![image](https://user-images.githubusercontent.com/34536372/114834164-e0964600-9e02-11eb-8ce2-da5ec48a85f4.png)

* 项目越权扫描结果展示界面

![image](https://user-images.githubusercontent.com/34536372/114835038-bf822500-9e03-11eb-8749-4701ac1313e2.png)





