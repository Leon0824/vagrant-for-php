# Vagrant php 开发环境



## initialize

```
# vagrant up
```
## nginx configure file

`./nginx-conf/` 保存nginx配置文件，改动后执行 `vagrant provision`

## www root

在 `./www-root/` 下创建指向 PHP 项目目录的软连接，此目录将挂载至 `/data/www-root/` 并属于 `www-data` 用户

## php includes

php include path包含 `./php-libs/` 目录




