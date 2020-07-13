docker-phpunit-hhvm
===================

<table>
        <tr>
            <td><img width="60" src="https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/book.svg" alt="publication" /></td>
            <td><strong>Archived Repository</strong><br />
            The code of this repository was written to illustrate the blog post <a href="https://marmelab.com/blog/2014/09/10/make-docker-command.html">Seamlessly Run Composer On HHVM Inside Docker: Introducing make-docker-command</a><br />
        <strong>This code is not intended to be used in production, and is not maintained.</strong>
        </td>
        </tr>
</table>

Run PHPUnit on HHVM within a docker container

So instead of running

    $ phpunit

You can run 

    $ docker run -ti -v `pwd`:/srv marmelab/phpunit-hhvm
