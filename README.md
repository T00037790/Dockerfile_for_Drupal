# Dockerfile_for_Drupal
Dockerfile for a Drupal installation

Resumen
-------

Esta imagen contiene:

* Apache 2.4
* MariaDB 10.1
* PHP 7.0
* Drush 8
* La última versión de Drupal Console para drupal 8.3.6
* Drupal 8.3.6
* Composer
* PHPMyAdmin
* Blackfire

¿Cómo usar?
-----------

Clonar el repositorio localmente y compilarlo:
- git clone https://github.com/T00037790/Dockerfile_for_Drupal.git
- cd Dockerfile_for_Drupal
- docker build -t "nombre_de_la_imagen" .

