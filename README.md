# Shadowrocket TikTok配置


&nbsp;

```
[URL Rewrite]
(?<=_region=)CN(?=&) JP 307
(?<=&mcc_mnc=)4 2 307
^(https?:\/\/(tnc|dm)[\w-]+\.\w+\.com\/.+)(\?)(.+) $1$3 302
(?<=\d\/\?\w{7}_\w{4}=)1[6-9]..(?=.?.?&) 18.4 307

[MITM]
hostname = *.tiktokv.com,*.byteoversea.com,*.tik-tokapi.com
```
&nbsp;


# 如何更改国家：
默认是日本区，可以更改这行代码中的JP (?<=_region=)CN(?=&) JP 307  
美国示例： (?<=_region=)CN(?=&) US 307  
英文简写 JP（日本）｜KR（韩国）｜UK（英国）｜US（美国）｜TW（中国台湾）  

# IOS看不了TikTok解决方法：
1、下载TikTok 21.1.0版本使用
## 2、插上手机卡，不要拔卡
