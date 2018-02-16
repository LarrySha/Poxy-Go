# Poxy-Go
<https://github.com/ginuerzh/gost>


###Serve:
wget -N --no-check-certificate https://github.com/LarrySha/Poxy-Go/releases/download/1.0/gost_2.5-rc1_linux_amd64.tar.gz
tar -xzvf gost_2.5-rc1_linux_amd64.tar.gz
apt-get install supervisor
mkdir -p /usr/local/var/log/
mkdir -p /usr/local/var/run/
supervisord -c supervisord.conf
supervisorctl start gost

supervisorctl stop gost

###Client
run.bat
