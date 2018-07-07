centOS 7:

switch kernel:

rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-3.10.0-229.1.2.el7.x86_64.rpm --force

reboot 

install severSpeed:

wget -N --no-check-certificate https://github.com/91yun/serverspeeder/raw/master/serverspeeder.sh && bash serverspeeder.sh

reference:
https://github.com/91yun/serverspeeder
https://www.91yun.co/archives/795

serverSpeeder command:
开始：service serverSpeeder start

停止：service serverSpeeder stop

重新加载配置：service serverSpeeder reload

重启：service serverSpeeder restart

状态：service serverSpeeder status

统计：service serverSpeeder stats

更新许可文件：service serverSpeeder renewLic

更新：service serverSpeeder update

卸载：service serverSpeeder uninstall

如无法查看统计，需要安装dc：yum install dc


	
