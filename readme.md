Fork Johnshall/Shadowrocket-ADBlock-Rules-Forever 制作的模块
自用规则，不适合他人引用

## 规则列表

![规则选择指南](https://johnshall.github.io/Shadowrocket-ADBlock-Rules-Forever/figure/guide.png)

规则 | 规定代理的网站 | 规定直连的网站 
--- | ----------- | ------------- 
[黑名单规则 + 去广告](#黑名单过滤--广告) |  被墙的网站（GFWList） | 正常的网站 
[黑名单规则](#黑名单过滤) |   |  
[白名单规则 + 去广告](#白名单过滤--广告) | 其他网站 | top500 网站中可直连的网站、中国网站 
[白名单规则](#白名单过滤) |   |  
[仅去广告规则](#仅去广告规则) |   |  

## 黑名单过滤 + 广告

黑名单中包含了境外网站中无法访问的那些，对不确定的网站则默认直连。

- 代理：被墙的网站（GFWList）
- 直连：正常的网站
- 包含广告过滤

规则地址：(shadowrocket://install?module={https://raw.githubusercontent.com/chas0000/MyShadowrocket_rule/release/sr_top500_banlist_ad.sgmodule})


## 白名单过滤 + 广告

白名单中包含了境外网站中可以访问的那些，对不确定的网站则默认代理。

- 直连：top500 网站中可直连的境外网站、中国网站
- 代理：默认代理其余的所有境外网站
- 包含广告过滤

规则地址：<shadowrocket://install?module={https://raw.githubusercontent.com/chas0000/MyShadowrocket_rule/release/sr_top500_whitelist_ad.sgmodule}>


## 黑名单过滤

现在很多浏览器都自带了广告过滤功能，而广告过滤的规则其实较为臃肿，如果你不需要全局地过滤 App 内置广告和视频广告，可以选择这个不带广告过滤的版本。

- 代理：被墙的网站（GFWList）
- 直连：正常的网站
- 不包含广告过滤

规则地址：<shadowrocket://install?module={https://raw.githubusercontent.com/chas0000/MyShadowrocket_rule/release/sr_top500_banlist.sgmodule}>

## 白名单过滤

现在很多浏览器都自带了广告过滤功能，而广告过滤的规则其实较为臃肿，如果你不需要全局地过滤 App 内置广告和视频广告，可以选择这个不带广告过滤的版本。

- 直连：top500 网站中可直连的境外网站、中国网站
- 代理：默认代理其余的所有境外网站
- 不包含广告过滤

规则地址：<shadowrocket://install?module={https://raw.githubusercontent.com/chas0000/MyShadowrocket_rule/release/sr_top500_whitelist.sgmodule}>


## 仅去广告规则

仅包含去广告规则，不包含代理/直连规则。用于与其他规则联用。

- 仅包含去广告规则，不包含代理/直连规则。无任何其他配置。

规则地址：<shadowrocket://install?module={https://raw.githubusercontent.com/chas0000/MyShadowrocket_rule/release/sr_ad_only.sgmodule}>



### 本项目引用：  
[gfwlist](https://github.com/gfwlist/gfwlist)  
[Greatfire Analyzer](https://github.com/Loyalsoldier/cn-blocked-domain)   
[乘风广告过滤规则](https://github.com/xinggsf/Adblock-Plus-Rule)  
[EasyList China](https://adblockplus.org/)  
[Peter Lowe 广告和隐私跟踪域名](https://pgl.yoyo.org/)   
[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)   
[Johnshall/Shadowrocket-ADBlock-Rules-Forever](https://github.com/Johnshall/Shadowrocket-ADBlock-Rules-Forever)
