# Convertible bond news
打新债信息推送机器人

# 推送方式
## [Server酱（微信）](http://sc.ftqq.com/3.version)
登录到Server酱，绑定微信之后，获取到sckey即可。
## [BARK（iOS）](https://github.com/Finb/Bark)
在AppStore下载BARK，获取到barkkey（机器码）即可。

# 使用
在[Release页面](https://github.com/Cyronlee/cbnew-go/releases)下载对应平台的可执行文件  
```bash
# sckey 和 barkkey 至少设置其中一个
cbnew.exe -sckey=XXXX -barkkey=XXXX

# 手动设置推送时间为 8:50，默认每天 9:00 分推送一次
cbnew.exe -sckey=XXXX -h=8 -m=50
```

# 数据来源
- [集思录](https://www.jisilu.cn/data/cbnew/#pre)
- [东方财富](http://data.eastmoney.com/kzz/default.html)

# 参考
[V2EX：cbnew-python](https://github.com/crazygit/cbnew)