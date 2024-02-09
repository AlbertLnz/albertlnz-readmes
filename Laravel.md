<!-- Username: AlbertLnz (Ctrl+ to select all) -->
<!-- Project: Readmes -->
<!-- RECOMENDACIÓN: En vez de usar esta plantilla con muchos pasos para iniciar el proyecto de Laravel, mejor crear un comando que los una -->


<div align="center">
  
  <!-- <img src="logo.png" height="90px" width="auto" />  -->

  <h2>Proyecto API de Laravel con MySQL</h2>

</div>

<div align="center">
    <a href="#🛠️-Stack">Stack</a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#⚗️-Requisitos">Requisitos</a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🚀-empezar">Empezar</a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🧞-comandos">Comandos</a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#💫-contributors">Contributors</a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🔑-licencia">Licencia</a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="https://github.com/AlbertLnz">GitHub</a>
</div>

<br />

<div align="center">

  [![Laravel][Laravel.com]][Laravel-url] [![MySQL]][MySQL-url]  [![PlanetScale]][PlanetScale-url]

  [Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
  [Laravel-url]: https://laravel.com

  [MySQL]: https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&labelColor=4479A1&logoColor=white
  [MySQL-url]: https://www.mysql.com/

  [PlanetScale]: https://img.shields.io/badge/planetscale-%23000000.svg?style=for-the-badge&logo=planetscale&logoColor=white
  [PlanetScale-url]: https://planetscale.com/

  ![GitHub stars](https://img.shields.io/github/stars/AlbertLnz/Readmes)
  ![GitHub issues](https://img.shields.io/github/issues/AlbertLnz/Readmes)
  ![GitHub forks](https://img.shields.io/github/forks/AlbertLnz/Readmes)
  ![GitHub PRs](https://img.shields.io/github/issues-pr/AlbertLnz/Readmes)

</div>

## 🛠️ Stack

- [**Laravel**](https://laravel.com) - Laravel - PHP Web Artisans
- [**MySQL**](https://www.mysql.com/) - MySQL


## ⚗️ Requisitos

- Git
- PHP^8.1
- Composer

## 🚀 Empezar

### 1. Clona este _[repo](https://github.com/AlbertLnz/Readmes)_ y ejecuta el comando:

```bash
git clone https://github.com/AlbertLnz/Readmes
```

### 2. Cambia el archivo _.env.example_ ➡️ _.env_

### 3. Pon el nombre de la base de datos:

```bash
DB:DATABASE=db_name
```

### 4. Instale las dependencia de Composer en el proyecto:

```bash
composer install
```

### 5. Genere una Key para su aplicación:

```bash
php artisan key:generate
```

### 6. Realize la migración:

```bash
php artisan migrate
```

### 7. Inserte datos de prueba _(opcional)_ :

```bash
php artisan migrate:fresh --seed
```

### 8. Instale Laravel Passport:

```bash
php artisan passport:install
```

### 9. Cree las credenciales de Personal Access Token:

```bash
php artisan passport:client --personal --name:"Personal Access Token"
```

### 10. ¡A ejecutar!:

```bash
php artisan serve
```

> [!NOTE]
> Cada vez que realize una nueva migración, debe de volver a generar a instalar Laravel Passport y las crendeciales de Personal Access Token (pasos 8 y 9)

1. Abre [**http://localhost:8000**](http://localhost:8000/) en tu navegador para ver el resultado 🚀


## 🧞 Comandos

|     | Comando          | Acción                                        |
| :-- | :--------------- | :-------------------------------------------- |
| ⚙️  | `php artisan serve`    | Lanza un servidor de desarrollo local en  `localhost:8000`.  |
| ⚙️  | `php artisan test --filter UserTest`          | Ejecuta los test.      |


## 💫 Contributors

| <img src="https://media.licdn.com/dms/image/D4D03AQE5TxlWN0RXsQ/profile-displayphoto-shrink_200_200/0/1697454522274?e=1712793600&v=beta&t=21ecQ6C_YtZs070Oo_i9_B6-wMQ0jNQqU5mhLXMN3Bs" style="height: 50px; display: flex; align-items: center;" height="50px" width="auto" /> | Albert Lanza Rio | [![LinkedIn][LinkedIn-Badge]][LinkedIn-URL-Person1] |
---|---|---|
| <img src="" style="height: 50px; display: flex; align-items: center;" height="50px" width="auto" /> | Matt Simons | [![LinkedIn][LinkedIn-Badge]][LinkedIn-URL-Person2] |
| <img src="" style="height: 50px; display: flex; align-items: center;" height="50px" width="auto" /> | Maria Johnson | [![LinkedIn][LinkedIn-Badge]][LinkedIn-URL-Person3] |

[LinkedIn-Badge]: https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white

[LinkedIn-URL-Person1]: https://www.linkedin.com/in/albert-lanza-rio/
<!-- Photo of Person 1 must insert in src manually! -->
[LinkedIn-URL-Person2]: https://www.linkedin.com/in/albert-lanza-rio/
<!-- Photo of Person 2 must insert in src manually! -->
[LinkedIn-URL-Person3]: https://www.linkedin.com/in/albert-lanza-rio/
<!-- Photo of Person 3 must insert in src manually! -->



## 🔑 Licencia

[MIT](LICENSE.txt) - Creado por [**AlbertLnz**](https://github.com/AlbertLnz).


