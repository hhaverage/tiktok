# Fiddler抓包工具代码：
&nbsp;

```
bpu MZBuy.woa
```

&nbsp;

TikTok版本号：21.1.0	      版本ID：844024073   
TikTok版本号：21.1.0	      版本ID：843972181


&nbsp;

&nbsp;

&nbsp;

&nbsp;

# Shadowrocket TikTok配置

```

[URL Rewrite]
(?<=_region=)CN(?=&) JP 307
(?<=&mcc_mnc=)4 2 307
^(https?:\/\/(tnc|dm)[\w-]+\.\w+\.com\/.+)(\?)(.+) $1$3 302
(^https?:\/\/*\.\w{4}okv.com\/.+&.+)(\d{2}\.3\.\d)(.+) $118.0$3 302

[MITM]
hostname = *.tiktokv.com,*.byteoversea.com,*.tik-tokapi.com

```
&nbsp;


# 如何更改国家：
默认是日本区，可以更改这行代码中的JP (?<=_region=)CN(?=&) JP 307  
美国示例： (?<=_region=)CN(?=&) US 307  
英文简写 JP（日本）｜KR（韩国）｜UK（英国）｜US（美国）｜TW（中国台湾）  

# IOS看不了TikTok解决方法：
#### 1、下载TikTok 21.1.0版本使用
#### 2、插上手机卡，不要拔卡
