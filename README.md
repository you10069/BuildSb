v# Build

iptables-nft

可以自行修改
sed -i 's/+firewall/+uci-firewall/g' feeds/luci/applications/luci-app-firewall/Makefile
然後make menuconfig手動去掉firewall，選擇firewall4
