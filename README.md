# Azure-Laravel-setup

>First create a app service with php version 

>Then connect your azure repo with it

>setup the pipeline 

>Test the pipeline with your changes

>ssh into the project and follow this 
```
https://azureossd.github.io/2021/09/02/php-8-rewrite-rule/index.html
```
>add a .htaccess in the root of the project
```
<IfModule mod_rewrite.c>
   RewriteEngine On 
   RewriteRule ^(.*)$ public/$1 [L]
</IfModule>
```

>Run service nginx restart
