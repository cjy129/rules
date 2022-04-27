# 目录
- [腾讯新闻](#腾讯新闻)
- [起点](#起点)
- [Spotify](#spotify)
- [哔哩哔哩](#哔哩哔哩)
- [贴吧](#贴吧)

## 腾讯新闻
> 不支持qx,脚本在qx上执行有问题,未解决
> 去开屏广告需要全新应用

| 软件 | 链接 |
| :-----| :---- |
| Surge | https://raw.githubusercontent.com/app2smile/rules/master/module/qqnews.sgmodule |
| Loon | https://raw.githubusercontent.com/app2smile/rules/master/plugin/qqnews.plugin |


## 起点
> 代理软件需全程开启,否则会出现去广告脚本始终无效的情况

解决办法(任选其一):
1. (推荐,*仅限Surge*): 打开Surge -> MITM的`配置根证书` -> `用于TCP链接` (保持开启状态), 然后杀掉起点app后台再重新打开一次. 随后就可以关闭`用于TCP链接`开关)
2. (*仅限Surge*): 若对自己手机上已MITM的域名比较了解,可以始终打开Surge -> MITM的`配置根证书` -> `用于TCP链接`
3. 删除起点app,重新下载安装使用

| 软件 | 链接 |
| :-----| :---- |
| Surge | https://raw.githubusercontent.com/app2smile/rules/master/module/qidian.sgmodule |
| Loon | https://raw.githubusercontent.com/app2smile/rules/master/plugin/qidian.plugin |
| qx | Rewrite:https://raw.githubusercontent.com/app2smile/rules/master/module/qidian.conf |


## Spotify
> 需要iOS15系统,Spotify音质不能设置为超高

| 软件 | 链接 |
| :-----| :---- |
| Surge | https://raw.githubusercontent.com/app2smile/rules/master/module/spotify.module |
| Loon | https://raw.githubusercontent.com/app2smile/rules/master/plugin/spotify.plugin |
| qx | Rewrite:https://raw.githubusercontent.com/app2smile/rules/master/module/spotify.conf |

## 哔哩哔哩
> 需要iOS15系统,Surge打开视频播放页面时有概率会出现播放页卡住的情况,返回重新打开视频即可

| 软件 | 链接 |
| :-----| :---- |
| Surge | https://raw.githubusercontent.com/app2smile/rules/master/module/bilibili.sgmodule |
| Loon | https://raw.githubusercontent.com/app2smile/rules/master/plugin/bilibili.plugin |
| qx | Rewrite:https://raw.githubusercontent.com/app2smile/rules/master/module/bilibili-qx.conf |


## 贴吧
> 需要iOS15系统,新回复等通知功能不可用,需手动点击App内的消息页查看

| 软件 | 链接 |
| :-----| :---- |
| Surge | https://raw.githubusercontent.com/app2smile/rules/master/module/tieba.sgmodule |
| Loon | https://raw.githubusercontent.com/app2smile/rules/master/plugin/tieba.plugin |
| qx | Filter:https://raw.githubusercontent.com/app2smile/rules/master/rule/tieba-ad-qx.list  <br> Rewrite:https://raw.githubusercontent.com/app2smile/rules/master/module/tieba-qx.conf |

