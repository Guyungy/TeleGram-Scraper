<p align="center">
  <img src="https://raw.githubusercontent.com/Guyungy/TeleGram-Scraper/master/.image/20191203_205322.jpg" width="470" height="150">
</p>

<p align="center"><img src="https://img.shields.io/badge/Version-3.1-brightgreen"></p>
<p align="center">
  <a href="https://github.com/Guyungy">
    <img src="https://img.shields.io/github/followers/Guyungy?label=Follow&style=social">
  </a>
  <a href="https://github.com/Guyungy/TeleGram-Group-Scraper">
    <img src="https://img.shields.io/github/stars/Guyungy/TeleGram-Group-Scraper?style=social">
  </a>
</p>
<p align="center">
  Telegram 群组爬取工具
</p>
<p align="center">
</p>

---
## 依赖
- telethon

## API 设置
* 打开并登录 http://my.telegram.org 
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

## 如何安装和使用

'git clone https://github.com/Guyungy/TeleGram-Scraper'

$ cd TeleGram-Scraper

安装需求
$ python3 setup.py -i

设置配置文件(apiID, apiHASH)
$ python3 setup.py -c

生成用户数据
$ python3 scraper.py

(如果更改了名称，则默认为members.csv)
向收集的数据发送批量短信
$ python3 smsbot.py members.csv

更新工具
$ python3 setup.py -u