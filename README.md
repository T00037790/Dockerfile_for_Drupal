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

     git clone https://github.com/T00037790/Dockerfile_for_Drupal.git
     cd Dockerfile_for_Drupal
     docker build -t "nombre_de_la_imagen" .
Luego de la compilación se creará una imagen como la siguiente:

![image](https://user-images.githubusercontent.com/21178320/29614096-8288f47a-87ce-11e7-9b55-319ab1a8fee6.png)
