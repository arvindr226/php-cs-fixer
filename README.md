# php-cs-fixer

To run the php-cs-fixer in you php code using docker please use the below command.

<pre>
$ docker run -it --rm -v $PWD:/app -w /app gotechnies/php-cs-fixer fix -v .
</pre>

The above command will mount your current directory code to docker container, execute the php-cs-fixer


