title: 安装
---

## 环境要求

- PHP >= 5.5.9 (其实你不必惊讶，PHP 7 的时代了)
- [PHP cURL 扩展](http://php.net/manual/en/book.curl.php)
- [PHP OpenSSL 扩展](http://php.net/manual/en/book.openssl.php)
- [PHP mcrypt 扩展](http://php.net/manual/en/book.mcrypt.php) 当启用加密消息时必选
- [PHP fileinfo 拓展](http://php.net/manual/en/book.fileinfo.php) 素材管理模块需要用到


Laravel 5 拓展包: [overtrue/laravel-wechat](https://github.com/overtrue/laravel-wechat)

## 安装

使用 [composer](http://getcomposer.org/):

```shell
$ composer require overtrue/wechat:~3.0 -vvv
```