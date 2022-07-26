<header class="pb-3 mb-4 border-bottom">
	<a href="/" class="d-flex align-items-center text-dark text-decoration-none">
		<img width="60" height="60" src="https://cdn-icons-png.flaticon.com/512/3408/3408740.png" class="custom-logo"></img>
		<span class="pt-8 mt-4">  </span>
	</a>
</header>

<div class="p-5 mb-4 bg-light rounded-3">
	<div class="container-fluid py-5">
		<h1 class="display-5 fw-bold"></h1>
		<p class="col-md-8 fs-4">App base usando laravel/livewire, para desarrollo de nuevas apps web</p>
		<button class="btn btn-primary btn-lg" type="button">Web oficial del proyecto</button>
	</div>
</div>

<div class="row align-items-md-stretch">
	<div class="col-md-6">
		<div class="h-100 p-5 text-white bg-dark rounded-3">
			<h2>Soporte</h2>
			<p>El soporte directo de Agencia Arte Digital</p>
			<button class="btn btn-outline-light" type="button">Arte digital</button>
		</div>
		<div class="h-100 p-5 text-white bg-dark rounded-3">
			<h2>Documentación</h2>
			<p>Todo app tiene que se debidamente documentada</p>
			<button class="btn btn-outline-light" type="button">Importante</button>
		</div>
	</div>
	<div class="col-md-6">
		<div class="h-100 p-5 bg-light border rounded-3">
			<h2>Contribuciones</h2>
			<p>Actualmente el proyecto está en desarrollo se irá actualizando</p>
			<button href="#" class="btn btn-outline-secondary" type="button">Ejemplos</button>
		</div>
	</div>
</div>

<footer class="pt-3 mt-4 text-muted border-top">
	Derechos reservados &copy; 2022
</footer>


## Acerca del projecto

Pasos para inmplementar el proyecto

<p>1-. Descargar/instalar laragon</p>
<p>2-. Decargar/instalar git</p>
<p>3-. Abrir git en el directorio www de laragon</p>
<p>4-. clonar repositorio "git clone https://github.com/ImhoDev/appbase.git"</p>
<p>5-. Desde la terminal de laragon/appbase instalar las dependencias de PHP "composer install"</p>
<p>6-. Desde la terminal de laragon/appbase instalar las dependencias de JS "npm install && npm run dev"</p>
<p>7-. Crear la base de datos "appbase" recomiendo usar phpmyadmin para crear la base de datos, o usar la consola de laragon "CREATE DATABASE appbase;"</p>
<p>8-. Duplicar y renombrar .env.example a .env</o>
<p>9-. Configurar el archivo .env con los datos de mysql</p>
<p>10-. Reinciar laragon desde la consola con "reload laragon" desde el escritorio principal de laragon que habitualmente es C:\laragon </p>
<p>11-. Vistar "http://appbase.test" desde cualquier navegador.</p>
<p>12-. Vemos que sale un error, hay que generar el key ejecuentado "php artisan key:generate"</p>
<p>13-. Sale error porque no hemos realizado las migraciones, para solucionar ejecutar las migraciones. </p>
<p>14-. Eliminar directorio oculto .git</p>
<p>15-. Crear un nuevo repositorio en el perfil de la agencia y realizar el primera commit</p>

