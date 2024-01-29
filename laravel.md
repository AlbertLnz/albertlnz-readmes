## Project title


## Stack

| Frontend        | [![Next][Next.js]][Next-url] [![Angular][Angular.io]][Angular-url] |
|---------------|:---------------------------------------------|

| Backend        | [![Next][Next.js]][Next-url] [![Angular][Angular.io]][Angular-url] |
|---------------|:---------------------------------------------|

| Database        | [![Next][Next.js]][Next-url] [![Angular][Angular.io]][Angular-url] |
|---------------|:---------------------------------------------|


## Getting Started

1. Fork or clone this repository

   ```bash
	git clone https://github.com/AlbertLnz/dice-API.git
	```

 2. Edit the **example.env** file to **.env** in our files and configure the DB migration:
	```bash
	DB:DATABASE=db_name
	```
 3. Be sure that you are inside the app:
	```bash
	cd dice-API
	```
 4. Execute the next command to download the project dependencies (you must have installed Composer[^1])
	```bash
	composer install
	```

 5. Generate a key for the application:
	```bash
	php artisan key:generate
	```
	
 6. Create the tables of the Database:
	```bash
	php artisan migrate
	```




<!-- -->

[^1]: [Oficial page of Composer](https://getcomposer.org/)

<!-- ASSETS -->
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/

[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
