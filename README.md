# TASKS

## About 

Este repositorio se realizó con el fin de aplicar los conocimiento de PHP + Laravel.


## Stack
Tecnologías utilizadas:
PHP + Laravel, Postman, Docker, MySQL Workbench
 
 ---

 ## Instalación 
1. Clonar el repositorio
2. Utilizar el comando ` $ composer install`
3. Conectamos nuestro repositorio con la base de datos 
4. ``` $ Ejecutamos las migraciones: php artisan migrate``` 
5. ``` $ Ejecutamos los seeders:  php artisan db:seed``` 
6. ``` $ php artisan serve ``` 

---

## Endpoints

<details>
<summary>Endpoints</summary>

- AUTH

- REGISTRAR USUARIO

       POST http://localhost:8000/api/register

  body:

  ```JSON
   {
       "name": "Luisito",
       "email": "luis@gmail.com",
       "password": "password"
   }
  ```

- LOGIN

       POST  http://localhost:8000/api/login

  body:

  ```JSON
  {
      "email": "luis@gmail.com",
      "password":"password"
  }
  ```

- TASKS

- VER TAREAS

        GET  http://localhost:8000/api/tasks


- CREAR TAREA

        POST  http://localhost:8000/api/tasks

body:

 ```JSON
  {
      "title": "Realizar CRUD de tareas",
      "description":"Fecha de entrega 30-06-2023"
  }
  ```

- MODIFICAR TAREA

       PUT  http://localhost:8000/api/tasks/20

body:

 ```JSON
  {
      "title": "Realizar CRUD ",
      "description":"Entrega 28-06-2023"
  }
  ```
- ELIMINAR TAREA

       DELETE  http://localhost:8000/api/tasks/10







ADMIN
  
- VER TODOS LOS USERS REGISTRADOS

        GET  http://localhost:8000/api/users

- AGREAGAR USUARIO A TAREA

      PUT  http://localhost:8000/api/add-user-to-task/10

- ELIMINAR USUARIO DE TAREA

      PUT  http://localhost:8000/api/delete-user-to-task/5/10

- VER TAREAS DE UN USER

        GET  http://localhost:8000/api/get-task-users/10



## Contacto



**_Francisco Campana_**  
<a href="https://github.com/FranciscoCampana1" target="_blank"><img src="https://img.shields.io/badge/github-24292F?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>

<a href="mailto:campanafrancisco1@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>

<a href="https://www.linkedin.com/in/francisco-campana-06b946273/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>

</p>