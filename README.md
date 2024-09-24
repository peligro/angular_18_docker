<hr />

<h1>Angular 18 con Docker</h1>
<p>
Ejecutar archivo Dockerfile:
<br/>
<code>docker-compose up</code>
<br/>
Se creará el proyecto con angular 18 y se desplegará en el puerto 4200
</p>
<hr />
<p>
Utilizando ng desde la terminal docker:
<br/>
<code>docker exec -it angular-app ng generate component componentes/header</code>
<br />
<code>docker exec -it angular-app ng g c componentes/footer -s</code>
</p>
<hr />

<p>
Detener contenedor:<br/>
<code>docker-compose down</code>
</p>
<hr />