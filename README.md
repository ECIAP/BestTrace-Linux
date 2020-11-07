# BestTrace for Linux 用法说明

通过SSH登录你的服务器
```
For RHEL / CentOS:
wget https://cdn.ipip.net/17mon/besttrace4linux.zip &&
yum install -y unzip zip &&
unzip besttrace4linux.zip &&
chmod +x besttrace

For Debian / Ubuntu:
wget https://cdn.ipip.net/17mon/besttrace4linux.zip &&
apt-get install -y unzip zip &&
unzip besttrace4linux.zip &&
chmod +x besttrace

用法:
./besttrace X.X.X.X
X.X.X.X 为IP地址，注意ipip.net有使用限制 如出现403则代表IP被拉黑
