# yii
php yii.1.1.19 框架 对php 7.2 的兼容处理
其它兼容方式参考下列地址
https://github.com/yiisoft/yii/issues/4182
一个题外问题,研究过mcrypt到openssl的兼容实现,但是限于微信端的加密问题,导致只能还是mcrypt加密,因为微信推送的数据是mcrypt处理的.openssl加密的数据,在mcrypt解密时,会多出一些空格,导致普通识别异常.
