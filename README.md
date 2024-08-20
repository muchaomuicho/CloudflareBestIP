# Cloudflare优选IP
优选Cloudflare高速节点，cf优选ip
# 本教程在github众多大佬的基础上结合，提供cf优选高速ip的思路，实测能跑满带宽
# 第一步 打开甬哥大佬的搭建cf节点教程：https://github.com/yonggekkk/Cloudflare_vless_trojan
按教程自行搭建节点，反代ip（proxyip）也可使用甬哥的反代ip优选工具
这时优选ip可使用甬哥的优选官方ip工具，但速度并不理想，所以就有了接下来的操作
# 第二步 打开https://github.com/snowfal1/CloudflareCDNFission
按教程跑代码，建议跑个三四次，确保ip数量满足你的要求
# 第三步 打开https://github.com/snowfall9/CloudflareST_auto_selector
下载测速工具，把上一步执行代码后的Fission_ip.txt中的内容复制到config文件夹中的fixed_ips.txt，再执行cf_dns_updater.exe
# 最后 延迟最低，速度最快的ip就在result.csv内了，导入到v2ray，享受速度的快感吧
最后的最后，喜欢就给个star吧
