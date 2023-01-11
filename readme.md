# 简介
Shadowrocket 的配置文件，每周四自动更新。
## 配置链接
### 白名单模式
```
https://raw.githubusercontent.com/TomKing062/Shadowrocket/master/Shadowrocket.conf
```
### 黑名单模式
```
https://raw.githubusercontent.com/TomKing062/Shadowrocket/master/Blacklist.conf
```
## 开启完整去广告（可选，不开启时为基础去广告）
导入配置后，点击`Shadowrocket.conf`或`Blacklist.conf`，选择`扩展配置`，在新配置中开启`HTTPS解密`，将证书导入系统并信任。
## 必装模块（生成的配置没有重定向功能，需要用模块实现）
```
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rewrite/Shadowrocket/SafeRedirect/SafeRedirect.sgmodule
```
## 可选模块
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/startup/startup.sgmodule
https://raw.githubusercontent.com/rartv/SurgeScript/main/EmbyPremiere/EmbyPremiere.sgmodule
