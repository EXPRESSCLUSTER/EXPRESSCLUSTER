# ESXi Commands memo for me
ESXiのネットワーク設定確認に使ったコマンドめも。

### esxcfg-route -l
送信ポート表示

### esxcfg-route -n
neighbor 表示  
https://orebibou.com/2014/06/vmware-esxi%E3%81%AE%E3%82%B3%E3%83%9E%E3%83%B3%E3%83%89%E3%83%AA%E3%83%95%E3%82%A1%E3%83%AC%E3%83%B3%E3%82%B9-esxcfg-route/

### tcpdump-w -i vmkX
tcpdump。dst/src host オプションとか使えなければ | grep でがんばる？  
https://kb.vmware.com/s/article/1031186?lang=ja

### esxcli network ip route ipv4
ifconfig

### esxcli network ip neighbor
arp -a
