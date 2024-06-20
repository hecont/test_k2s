# test_k2s
Prueba de Laravel
Video de muestra de funcionamiento: Productos.zip

Pasos para instalar la aplicación:
  * descargar el archivo test_k2s.zip
  * descomprimir en servidor apache (en mi caso, utilice xampp en la carpeta htcdocs).
  * crear base de datos en pstgresql con el nombre test_k2s.
  * modificar el archivo .env y colocar los parámetros del servidor que utilicen (DB_CONNECTION=pgsql DB_HOST=127.0.0.1 DB_PORT=5432 DB_DATABASE=test_k2s DB_USERNAME=postgres   DB_PASSWORD=123456), en mi caso.
  * iniciar la aplicacion en el navegador con la url http://127.0.0.1:8000/productos
