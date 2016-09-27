# docker-apache2-php-fat-image

As the name subtely suggests, this image is aimed at providing
all the php extensions you might dream of. I use it to test
php apps, which often require custom extensions.

It's by no means optimized; I suggest not using this overly bloated 
image in production. It's only meant to be a versatile test environment.


Build: 

```
docker build -t jbruggem/apache2-php-fat-image:latest .
```
