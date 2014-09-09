docker-phpunit-hhvm
===================

Run PHPUnit on HHVM within a docker container

So instead of running

    $ phpunit

You can run 

    $ docker run -ti -v `pwd`:/srv marmelab/phpunit-hhvm
