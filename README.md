# Odoo-Postgres-Docker

Creo un directorio al que he llamado “OdooSetup”, y dentro de dicho directorio creo el archivo 
“docker-compose.yml”.

En este dockerfile, creo dos contenedores. 
Uno para odoo, al que he llamado “odoo”, 
y otro para la base de datos con postgreSQL, al que he llamado “db”.
El puerto que he designado para Odoo es el 8069.
Luego, abro el terminal, y ya estando situado dentro del directorio OdooSetup, introduzco el 
siguiente comando:
docker-compose up
Se nos crean los contenedores con odoo y la base de datos.

A continuación, en la barra de direcciones del navegador, introduzco:
localhost:8069
(ya que el puerto designado en mi dockerfile es el 8069)
Y me redirigirá a la página de configuración de Odoo, donde rellenaré los campos correspondientes 
y luego click en “Create database”.

Una vez creada la base de datos, se mostrará la página con todas las aplicaciones disponibles.
