https://blog.birost.com/a?ID=01250-bdbd4116-3e16-4a51-bba6-b56beb5cc1da

http://pecl.php.net/get/memcache-4.0.5.2.tgz

wget http://pecl.php.net/get/memcache-4.0.5.2.tgz

tar zxvf memcache-4.0.5.2.tgz

cd memcache-4.0.5.2

/usr/local/php/bin/phpize

OR

/opt/bitnami/php/bin/phpize 


./configure --with-php-config=/usr/local/php/bin/php-config

OR

./configure --with-php-config=/opt/bitnami/php/bin/php-config

make

sudo make install



/usr/local/php/bin/php -m

OR

/opt/bitnami/php/bin/php -m


sudo /opt/bitnami/ctlscript.sh restart
