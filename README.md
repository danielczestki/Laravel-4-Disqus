Laravel-4-Disqus
================

Laravel 4 Disqus package

a package to embed disqus comment to your laravel application.

add this line to your app.php provider array:

'Totox777\Disqus\DisqusServiceProvider',


and add this line to app.php aliases array:

'Disqus' => 'Totox777\Disqus\Facades\Profiler',



config:
don't forget to chage the disqus short_name in src/config/config.php


Usage:

Disqus::getHtml();
