
## Instalación

### Composer
cd /tmp
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
**LOGIN AGAIN**
(https://www.epictrim.com/ideas/install-composer-on-centos/)

### Paquetes vendor
sudo composer install

---

### Estructura
from https://www.merixstudio.com/blog/laravel-5-tutorial/

- app: this is the heart of our application.
-- HTTP: everything related to accessing our application from the web goes here.
-- Providers: contains providers - classes responsible for loading and management of our application.
- bootstrap: contains Laravel’s initialization files.
- config: this is where our application configuration is placed.
- public: this is a special folder that contains files that are directly available from the web.
- routes: this contains our routing.
- storage: this is where our application store its data. Make sure to give the app write permission to this folder.

### Login por token JWT incorporado
https://github.com/tymondesigns/jwt-auth/wiki/Installation

### Como llamar a la api:
add 'public/controller/method' after url

### Para testear la api:
/api_test.html

### Para añadir clases de uso común
"Create a 'Libraries' folder inside your app folder"
https://stackoverflow.com/a/17091089/2075591

---

Seed:
https://github.com/simpl-e/simple_lumen_seed.git

Para migrarlo a cualquier versión de laravel o lumen copiar los archivos excepto /public/* y revisar bootstrap/app.php
