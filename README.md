# LAMP
Entorno LAMP con múltiples versiones de Php en Dockerfile


Entorno LAMP con multiples posibilidades versiones de PHP

Se incluye scritp para faciltar el cambio entre versiones sin modificar el archivo ".env" [ bash cambiar.sh]

Para comenzar a utilizar usar el comando cp plantilla.env .env

Si se modifica el archivo .env prestar atención a la linea de la variable VERSION_PHP que por defecto es la 8 ya que si no esta en esa linea el
script no funcionará. Modificar los comandos sed del script si la variable cambia de número de linea.
