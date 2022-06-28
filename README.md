# clash-daimao
[风俗]

;tutu规则公开公开版本public 关注频道可见更多版本。频道@hututu00

;欢迎使用tutu的规则！现在接受规则自定义计划随心所欲定制你自己的规则。

;✉️telegramtelegram0 💰️美元定制冲突保证一年后9999年有更新的服务时间@hututututu0，需要请按当时的价格续订。

;规则更新售后频道telegram @hututu00

;规则更新售后频道telegram @hututu00

;规则更新售后频道telegram @hututu00

ruleset=🗽 大陆服务，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/LocalAreaNetwork.list

ruleset=🗽 大陆服务，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/UnBan.list

规则集=🍃 AD,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Advertising/Advertising.list

ruleset=🌐 Google FCM，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/GoogleFCM.list

ruleset=🗽 大陆服务，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/GoogleCN.list

ruleset=🗽 大陆服务，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/SteamCN.list

规则集=👩‍💻 OneDrive，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/OneDrive.list

规则集=🧑‍💻 微软，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Microsoft.list

ruleset=☁️ iCloud Private Relay，https://raw.githubusercontent.com/LeeZe7/-Clash-/main/Rules/iCloudPrivateRelay.list

规则集=❤️‍🔥 Speedtest，https://raw.githubusercontent.com/bunizao/rulelist1/main/speedtest.list

规则集=📰 新闻，https://raw.githubusercontent.com/LeeZe7/-Clash-/main/Rules/AppleNews.list

ruleset=🔍 Spot-Wiki，https://raw.githubusercontent.com/bunizao/rulelist1/main/Spot-Wiki.list

规则集=💵 PayPal，https://raw.githubusercontent.com/LM-Firefly/Rules/master/PROXY/PayPal.list

规则集= 苹果，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Apple.list

ruleset=✉️ Telegram，https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Telegram/Telegram.list

规则集=🎮 Gamehub，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Epic.list

规则集=🎮 Gamehub，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Sony.list

规则集=🎮 Gamehub，https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Steam/Steam.list

规则集=📹 YouTube，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/YouTube.list

规则集=📹 YouTube，https://raw.githubusercontent.com/bunizao/rulelist1/main/google_search.list

规则集=🎥 Netflix，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Netflix.list

规则集=🎥 Disney+,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/DisneyPlus.list

规则集=🎵 Spotify，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Spotify.list

规则集=🎬 TikTok，https://raw.githubusercontent.com/LeeZe7/-Clash-/main/Rules/TikTok.list

ruleset=🧣 微博，https://raw.githubusercontent.com/LeeZe7/-Clash-/main/Rules/Weibo.list

规则集=🕊️ Twitter，https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Twitter/Twitter.list

规则集=📺 Bahamut，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Bahamut.list

规则集=📺哔哩哔哩，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/BilibiliHMT.list

规则集=📺哔哩哔哩，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Bilibili.list

ruleset=🌏 主页，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaMedia.list

ruleset=🌍 国外，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyMedia.list

ruleset=🚀节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list

;ruleset=🗽 大陆服务，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaIp.list

ruleset=🗽 大陆服务，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaDomain.list

ruleset=🗽 大陆服务，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaCompanyIp.list

ruleset=🗽 大陆服务，https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Download.list

;ruleset=🗽 大陆服务,[]GEOIP,LAN

ruleset=🗽 大陆服务,[]GEOIP,CN

规则集=❄️,[]FINAL

;设置规则标志位

; 设置分组标志位

custom_proxy_group=❄️`select`[]DIRECT`[]⚡️ 自动

custom_proxy_group=🚀韩国节点选择`select`[]⚡️自动`[]🇭🇰香港`[]🇨🇳台湾`[]🇸🇬狮城`[]🇯🇵日本`[]🇺🇲美国`[]🇰🇷` []👾手动切换`[]DIRECT

custom_proxy_group=👾 手动切换`select`.*

custom_proxy_group=⚡️ 自动`url-test`.*`http://www.gstatic.com/generate_204`300,,60

custom_proxy_group=✉️ Telegram`select`[]⚡️ 自动`[]🗽 大陆服务`[]👾 手动切换

custom_proxy_group=📹 YouTube`select`[]⚡️ 自动`]🚀节点选择`[]🪞 YouTube

custom_proxy_group=🎥 Netflix`select`[]🌊 Stream`[]🇸🇬 狮城`[]🇭🇰 香港`[]🇨🇳 台湾`[]🇯🇵 日本`[]🇺🇲 美国`[]🇰🇷 `[ ]👾手动切换

custom_proxy_group=🎥 Disney+`select`[]🌊 Stream`[]🇸🇬 狮城`[]🇭🇰 香港`[]🇨🇳 台湾`[]🇯🇵 日本`[]🇺🇲 美国`[]🇰🇷 `[ ]👾手动切换

custom_proxy_group=🎵 Spotify`select`[]🗽 大陆服务`[]🇨🇳 台湾`[]🇭🇰 香港

custom_proxy_group=📺 Bahamut`select`[]🇨🇳 台湾`[]🇨🇳 TW*

custom_proxy_group=📺 Bilibili`select`[]🗽 大陆服务`[]🇨🇳 台湾`[]🇭🇰 香港

custom_proxy_group=🧣微博`select`[]DIRECT`[]🇭🇰香港`[]🇨🇳台湾`[]🇸🇬狮城`[]🇯🇵日本`[]🇺🇲美国`[]🇰🇷韩国`[] 👾手动切换

custom_proxy_group=🎬 TikTok`select`[]🇨🇳 台湾`[]🇸🇬 狮城`[]🇯🇵 日本`[]🇺🇲 美国`[]🇨🇳 TW*`[]🇸🇬 SG*`[]🇯🇵 JP*`[]🇺🇲 美国*

custom_proxy_group=🕊️ Twitter`选择`[]⚡️ 自动`[]👾 手动切换

custom_proxy_group=❤️
