Para inicializar git
    git init
    
Para ver si hay cambios
    git status
    
Para agregar cambios a commit
    git add .

Para hacer commit
    git commit -m "Descripción del commit"

Para ver el log de git
    git log

Para ver el origen de git: 
    git remote -v

Para asignar el origen de git:
    git remote add origin https://github.com/sahlom/laravelAdmin.git

Para subir a git los cambios en la rama master
    git push origin master

Para ver ramas existentes
    git branch
    
Para crear una rama crudUsuarios
    git checkout -b crudUsuarios


///////////////////////////////

1. Descargamos el repositorio de github

2. Creamos el archivo .env

3. Configuramos bases de datos

4. Instalamos requerimientos de laravel a traves de composer:
    composer update
    ó
    composer install
    
5. Agregamos la llave de laravel
    php artisan key:generate

6. Instalamos dependencias NPM
    npm intall
    
7. Ejecutamos el servidor
    php artisan serve

