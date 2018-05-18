# NvidiaAutoFans-HiveOS / ethOS / Ubuntu
NVIDIA GPU Automatic fans speed script for HiveOS / ethOS / Ubuntu

# Easy Setup #1

1. Connect to your rig via SSH or Teleconsole <br>
2. Next, enter a set of commands:<br>
```
cd /home/user/
```
Put autofan.sh and xinit.user.sh to /home/user/ folder or Download

### Downalod 
```
wget http://vitosap.ru/fan.sh
wget http://vitosap.ru/xinit.user.sh
```
### Change permissions to -rwxr-xr-x (755)
```
chmod +x /home/user/fan.sh
chmod +x /home/user/xinit.user.sh
```

Done!

3. Functional test:
```screen -r fan```
Should see the script working

4. Edit fans config:
```nano /home/user/fan.sh```

Only change these settings
```
MIN_TEMP=60 
MAX_TEMPP=70 

MIN_COEF=80
MAX_COEF=110
```
If you need a more aggressive fan mode, first try increasing MIN_COEF=85

# Community

http://t.me/formining

# Donate
4mining.ru - Nvidia AutoFans Script - HiveOS / ethOS / Ubuntu

BTC donate: 15Kwt97RuqnJhWi1bQaGH7m43T3gXjcZFD <br>
ETC donate: 0x092f601ac0e475809987164986f27c20245d72ca <br> 
ETH donate: 0x425e6b94efc720f61a5e1b22c2710476e64d9221 <br> 
XMR donate: 463tWEBn5XZJSxLU6uLQnQ2iY9xuNcDbjLSjkn3XAXHCbLrTTErJrBWYgHJQyrCwkNgYvyV3z8zctJLPCZy24jvb3NiTcTJ <br> 
ZEC donate: t1UwudzgKp9hegkkkdPqQuroT7sMu8QxMGk <br> 
