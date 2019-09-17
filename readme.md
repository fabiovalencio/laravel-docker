<h1>
    <br>
    <a href="https://www.docker.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/0e507e36536396ee57530a9b5e9bb651a368ea3c/68747470733a2f2f6b6f6e70612e6769746875622e696f2f64657669636f6e2f64657669636f6e2e6769742f69636f6e732f646f636b65722f646f636b65722d6f726967696e616c2d776f72646d61726b2e737667" alt="Docker" width="100" data-canonical-src="https://konpa.github.io/devicon/devicon.git/icons/docker/docker-original-wordmark.svg" style="max-width:100%;"></a>
    <a href="https://laravel.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/fd7b6ef68bb8add9c3ace6bd735e01d16f5f5af3/68747470733a2f2f6b6f6e70612e6769746875622e696f2f64657669636f6e2f64657669636f6e2e6769742f69636f6e732f6c61726176656c2f6c61726176656c2d706c61696e2d776f72646d61726b2e737667" alt="Laravel" width="100" data-canonical-src="https://konpa.github.io/devicon/devicon.git/icons/laravel/laravel-plain-wordmark.svg" style="max-width:100%;"></a>
</h1>

## Laravel applications with Docker

This repo contains a Laravel installation setup to use Docker to create a development environment. This repo can be used as a starting point for developing Laravel apps with Docker.

You can check this medium post out for more information.

This setup contains;





<ul>
<li>PHP-FPM (PHP 7)</li>
<li>Nginx web server</li>
<li>Redis</li>
<li>MySQL database</li>
</ul>


[Laravel documentation](https://laravel.com/docs/contributions).

## Run

Make sure your have [Composer](https://getcomposer.org) and [Docker](https://docker.com) installed

Clone repo
<pre>
    <code>$ git clone https://github.com/fabiovalencio/laravel laravel && cd laravel</code>
</pre>

Build and run the Docker containers
<pre>
    <code>docker-compose up -d</code>
</pre>



<b>Wait for Composer installation it can take a while</b>

<b>The service will run on localhost: 8000</b>
## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
<p>Code and documentation copyright 2017 Docker, inc, released under the Apache 2.0 license.</p>
