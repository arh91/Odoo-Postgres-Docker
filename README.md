# Odoo-Postgres-Docker

Creo un directorio al que he llamado “OdooSetup”, y dentro de dicho directorio creo el archivo 
“docker-compose.yml”.

En este dockerfile, creo dos contenedores. 
Uno para odoo, al que he llamado “odoo”, 
y otro para la base de datos con postgreSQL, al que he llamado “db”.
El puerto que he designado para Odoo es el 8069.



![Captura de pantalla (70)](https://user-images.githubusercontent.com/32130215/214528914-c5432f03-b79a-4fc1-9193-700e000447af.png)


![Captura de pantalla (71)](https://user-images.githubusercontent.com/32130215/214529191-c54f8acb-6c8d-416b-9f48-5e3c68e277d4.png)


Luego, abro el terminal, y ya estando situado dentro del directorio OdooSetup, introduzco el 
siguiente comando:
docker-compose up
Se nos crean los contenedores con odoo y la base de datos.

A continuación, en la barra de direcciones del navegador, introduzco:
localhost:8069
(ya que el puerto designado en mi dockerfile es el 8069)
Y me redirigirá a la página de configuración de Odoo, donde rellenaré los campos correspondientes 
y luego click en “Create database”.

![Captura de pantalla (74)](https://user-images.githubusercontent.com/32130215/214529449-5a8a43a4-a4b1-4eb3-b056-d4e0198e9eb2.png)


Una vez creada la base de datos, se mostrará la página con todas las aplicaciones disponibles.

![Captura de pantalla (75)](https://user-images.githubusercontent.com/32130215/214529545-c385f172-b4ea-4d15-ac2a-eb40abc4be82.png)

