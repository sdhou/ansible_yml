## server
- 123.59.80.156 app02
- 123.59.80.155 app01
- 123.59.80.157 job
- 123.59.80.164 test
- 123.59.80.166 gitlab
- 123.59.80.161 lb
- 180.150.178.177 app04
- 180.150.179.19 app03

## phpbrew
```
phpbrew -v -d install 7.2.0 +default +sqlite +mysql +pdo +fpm +gd
apt install libxml2-dev libssl-dev libbz2-dev libcurl4-gnutls-dev libpng++-dev libreadline-dev libxslt1-dev
```
