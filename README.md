# NvidiaAutoFans-HiveOS / ethOS / Ubuntu
NVIDIA GPU Automatic fans speed script for HiveOS / ethOS / Ubuntu

# Easy Setup #1
0. 
1. Connect to your rig via SSH or Teleconsole
2. Next, enter a set of commands:
* cd home/user/
* wget http://vitosap.ru/fan.sh
* wget http://vitosap.ru/xinit.user.sh
* chmod +x /home/user/fan.sh
* chmod +x /home/user/xinit.user.sh

Done!

3. Functional test:
* screen -r fan
Should see the script working

4. Edit fans config:
* nano /home/user/fan.sh

Only change these settings

MIN_TEMP=60
MAX_TEMP=70

MIN_COEF=80
MAX_COEF=110

If you need a more aggressive fan mode, first try increasing MIN_COEF=85



