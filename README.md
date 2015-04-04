## About

This is an example of integrating a PHP application with the Jenkins PHP template (http://jenkins-php.org/). 
Read more at http://systemsarchitect.net/continuous-integration-for-php-with-jenkins/ 

IMPORTANT: Please ignore the "vendor/bin/phing -logger phing.listener.NoBannerLogger" and "Delete Invoke Ant" instructions, when doing the steps explained on systemsarchitect.net

Please make sure the 

## Installation

```
php composer.phar install
ln -s $PWD/vendor/bin/pdepend /usr/local/bin/pdepend
ln -s $PWD/vendor/bin/phpcbf /usr/local/bin/phpcbf
ln -s $PWD/vendor/bin/phpcpd /usr/local/bin/phpcpd
ln -s $PWD/vendor/bin/phpcs /usr/local/bin/phpcs
ln -s $PWD/vendor/bin/phpdox /usr/local/bin/phpdox
ln -s $PWD/vendor/bin/phploc /usr/local/bin/phploc
ln -s $PWD/vendor/bin/phpmd /usr/local/bin/phpmd
ln -s $PWD/vendor/bin/phpunit /usr/local/bin/phpunit
```



