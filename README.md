每天自动0点与官方bpb同步最新代码
# <a href="https://youtu.be/sWy9gCBA5Lo" rel="nofollow">视频教程</a>

新建一个私人仓库，项目可随意命名，但要避开 BPB 敏感词。
在该项目创建(  .github/workflows/Obfuscate.yml)。
复制创建仓库源码.js的代码，粘贴到项目，保存。
点击Obfuscate.yml旁边的小黄点同步到 BPB 代码，同步完成生成_worker.js与origin.js，前者是混淆代码，后者是明文代码。如果找不到小黄点，请前往：你的项目→Actions→左边的Build Obfuscate BPB Panel→中间的Build Obfuscate BPB Panel的工作流文件是否有效。
到Cloudflare里创建Pages+github，找到刚刚的 github 项目，用其创建 Pages 项目，并修改下面的变量及绑定 kv 空间。
引用请注明出处：SO启程Github。


# 变量的使用
@.CF 变量增加三个变量
## 1.UUID，<a href="https://1024tools.com/uuid" rel="nofollow">在线生成</a>。
PROXYIP，来源于网络分享：proxy.xxxxxxxx.tk、edgetunnel.anycast.eu.org、ts.hpc.tw、cdn.xn--b6gac.eu.org、cdn-all.xn--b6gac.eu.org、bestproxy.onecf.eu.org。
## 2.TR_PASS，默认要修改的密码。
## 3.SUB_PATH
kv，(小写字母)绑定KV命名空间。
/panel，部署成功后，在 url 后面增加/panel来进行访问面板，访问面板修改的密码将会保存在kv对里。
IP优选工具的使用
win 电脑下载IP优选工具/CF优选官方IP[win电脑版].7z，解压后，退出VPN，运行本软件。
下载<a href="https://github.com/bia-pain-bache/Cloudflare-Clean-IP-Scanner/releases/tag/v2.2.5">CloudflareScanner</a>，解压后，退出VPN，运行本软件。
特别感谢
bia-pain-bache
