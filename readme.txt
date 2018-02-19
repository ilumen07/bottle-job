EXECUTOR_NUMBER=1
cd /var/www/html/
sudo git pull https://github.com/ilumen07/Bottle.git
sudo kill -9 `pidof python3 superbottle`
sudo nohup python3 superbottle &
