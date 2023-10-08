# 主打的就是免费！尊嘟假嘟？统计了全球诸多的免费API，做一个API的搬运工，不定时更新新接口。您的star是我一直维护的动力。尊嘟！

## 2023-10-7

### 脏话
- 不同等级脏话：https://act.jiawei.xin:10086/lib/api/maren.php?catalog=yang 。入参:[common:普通等级,qiu:礼貌用语,yang:骂娘等级,默认:common]
- 纯文本返回：https://act.jiawei.xin:10086/lib/api/maren.php?format=json 。入参:[json,js,默认:纯文本]
- 不同格式返回：https://act.jiawei.xin:10086/lib/api/maren.php?charset=gbk2312 。入参:[utf8,gbk2312,默认:utf8]

### 头像
- svg格式头像：https://api.multiavatar.com/xxx.svg 。入参:[xxx:随机值]
- png格式头像：https://api.multiavatar.com/xxx.png 。入参:[xxx:随机值]

### 休息日
- 下一个休息日：https://wangxinleo.cn/api/wx-push/holiday/getHolidaytts

### 每日一言
- 金山词霸：https://open.iciba.com/dsapi
- 支持分类过滤：https://v1.hitokoto.cn/?c=e 。入参:[a:动画,b:漫画,c:游戏,d:小说,e:原创,f:网络,g:其他]
- 沙雕语言：https://api.shadiao.pro/chp 。入参:[chp:彩虹屁,pyq:朋友圈文案,du:毒鸡汤]
- 古诗文：https://v2.jinrishici.com/sentence 或者：https://v2.jinrishici.com/one.json
- 一句古诗文：https://v2.jinrishici.com/one.svg
- 毒鸡汤：https://api.oick.cn/dutang/api.php
- 社会经典语录：https://api.oick.cn/yulu/api.php
- 舔狗日记：https://api.oick.cn/dog/api.php
- 历史上的今天：https://api.oick.cn/lishi/api.php
- ip签名：https://api.oick.cn/netcard/api.php

### 城市天气
- 最近天气指标：http://t.weather.itboy.net/api/weather/city/xxx 。入参:[xxx:中国天气城市代码编号,如：101210101(参考：https://blog.csdn.net/u013634862/article/details/44886769)]

### 图片
- bing每日壁纸数据：https://cn.bing.com/HPImageArchive.aspx?format=js&idx=0&n=1
- bing每日壁纸图片：https://api.oick.cn/bing/api.php
- 二次元随机图：https://api.oick.cn/random/api.php?type=pc 。入参:[pc:电脑壁纸,pe:手机壁纸,默认:pc]
- 自定义内容的二维码：https://api.oick.cn/qrcode/api.php?text=http://www.oick.cn&size=100px 。入参:[text:二维码内容(链接请带Http/Https),size:二维码大小(px)]

### 音乐
- 网易云音乐下载：https://api.oick.cn/wyy/api.php?id=1966155051 。入参:[id:网易云歌曲ID]
- 网易云音乐热门评论：https://api.uomg.com/api/comments.163?format=json&mid=1 。入参:[format:json/text;mid:网易云歌单ID]
- 全民K歌音乐下载：https://api.uomg.com/api/get.kg?songurl=https://node.kg.qq.com/play?s=YaCv8EYfJunVWYcH 。入参:[songurl:要解析的歌曲链接,format:输出方式json,text,file,默认:json]

### 语音
- 文字转语言：https://api.oick.cn/txt/apiz.php?text=零七生活&spd=1 。入参:[text:转换的文字或英文,长度<=1000个字符,spd:语速,取值0-15,默认为5中语速,越大越快]

### 视频
- 短视频地址：https://api.oick.cn/video/api.php?url=https://v.douyin.com/UXwmhDM/ 。入参:[url:要解析的视频地址]

### 域名
- 检测域名是否拦截：https://api.oick.cn/t/api.php?url=baidu.com 。入参:[url:要查询的域名]
- 防红链接：https://api.uomg.com/api/long2fh?dwzapi=urlcn&url=http://qrpay.uomg.com 。入参:[url:需要进行防红的长网址,dwzapi:选择缩短接口,tcn,dwzcn,urlcn,suoim,mrwso]
- 检测域名是否被墙：https://api.uomg.com/api/ck_qiang?domain=google.com 。入参:[domain:查询的域名]

### IP
- 本机ip：https://api.ipify.org?format=json 或者 https://api64.ipify.org?format=json 。入参:[format:text|json|jsonp]

### 电话
- 骚扰电话检测：https://api.oick.cn/phone/api.php?phone=15677246297 。入参:[phone:手机号]

### 网盘
- 蓝奏云解析：https://api.oick.cn/lanzou/api.php?url=https://wwa.lanzoui.com/iaxxjsd 。入参:[url:蓝奏云盘分享链接;type:是否直接下载,值:down;pwd:外链密码]


