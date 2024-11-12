Pepe, al iniciar el dokcer, primero habras de crear el .env dentro de 2dam_inventory con estos datos:
WEB_SERVER_PORT=8080
MYSQL_DATABASE=inventory
MYSQL_USER=inventory_uder
MYSQL_PASSWORD=admin
MYSQL_ROOT_PASSWORD=admin

A continuacion has de levantar el docker desde la carpeta Docker_PMDM_Proyecto con: docker-compose up -d

Luego habaras de enviar los seeders desde la carpeta 2dam_inventory con: npm run seeds
