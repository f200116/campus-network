# 深澜软件校园网登录(升达为例)
针对郑州升达经贸管理学院校园网自动登录制作的python脚本  

## 安装依赖
`pip install requirements.txt`

## 软件生成的文件介绍
```
info.json
{
  "username": "202004060140",
  "password": "111111",
  "init_url": "218.198.32.106"
}

username：学号
password：密码（默认为身份证号后6位）
init_url：校园网登录网址（升达的不用改）
```

# 开机自动连接校园网教程

1. 下载编译完成的软件（或者自己下载代码之后进行本地编译）并打开测试软件是否可用 软件第一次运行会在同级文件夹内生成一个json文件用来储存用户的个人信息
2. 把软件单独放到一个能找到的文件夹中，文件夹最好不要有其他东西，此文件夹也不要移动、删除。
3. 创建软件的快捷方式，然后把快捷方式拖到`启动`文件夹中。打开启动文件夹的方式建议以下两种：  
    1. 找到以下目录把快捷方式拖放进去：
         ```
        C:\Users\用户名\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
        例：
        C:\Users\Q1654\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
        注：C为Win10系统盘盘符
        ```
    2. 打开`运行`对话框(按下win+R)之后输入`shell:startup`，点击确定即可打开启动文件夹。
        ```
        shell:startup
        ```
4. 重启电脑，软件自动运行。  
  
    

## 结语
<font size=5>如果觉得对你有所帮助的话<br>请给我一个小小的star。谢谢！<br>如果不明白的地方欢迎随时提问。</font>   
bilibili：[爱睡觉的波比鸭](https://space.bilibili.com/57254257?spm_id_from=333.337.0.0) **:point_left:**
