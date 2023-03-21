

### PERHATIAN
- Thank you for neither selling nor encrypting this script. I got it for free, so I or you guys have to share it for free.
- This script is **not recommended for gaming**.
- Service status sometimes miss information. Where the status is dead but if seen by the service the status is already active. So it can be ignored
- If you get an error on the service status in the long term, you can restart the dead service.

### INSTALL SCRIPT
<pre><code>apt install -y wget screen && wget -q https://raw.githubusercontent.com/RolkosModai/scriptvps/master/main.sh && chmod +x main.sh && screen -S install ./main.sh</code></pre>

Re-access 15 after the installation process. **Re-access via ssh using port 39**

### TESTED ON OS 
- UBUNTU 20.04.05

### FITUR TAMBAHAN
- Add 1GiB Swap
- Dynamic installation
- Tuning profiles on the server
- Xray Core by [@dharak36](https://github.com/dharak36/Xray-core)
- Added fail2ban
- Auto block some Indo ads by default

### PORT INFO
```
- TROJAN WS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- VLESS WS 443
- VLESS GRPC 443
- VLESS NONTLS 80
- VMESS WS 443
- VMESS GRPC 443
- VMESS NONTLS 80
- SSH WS / TLS 443
- SSH NON TLS 8880
- OVPN SSL/TCP 1194
- SLOWDNS 5300
```

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```
### STATUS
`Beta Testing`

### Lisensi
Repository ini dilindungi oleh lisensi [MIT](https://mit-license.org/)

### Credits
- [Dharak36](https://github.com/dharak36/Xray-core)
- [Tiarap](https://github.com/pengelana/blocklist)
