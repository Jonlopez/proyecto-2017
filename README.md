# Proyecto DAM 2017 Aitor y Jon

Repositorio del módulo de proyecto de Desarrollo de Aplicaciones Multiplataforma en [Egibide Arriaga](http://www.egibide.org/2/es/25/donde-nos-encontramos.html).

La carpeta [docs](./docs/) contiene el [sitio web](https://egibide-dam.github.io/proyecto-2017/) con la documentación.

## Pasos a seguir para poner en funcionamiento el sistema

### Entorno servidor

* Descargar el archivo vlampp.box
* Abrimos consola de comandos no situamos en el path que queramos instalar nuestro vagrant.box
```
   :~$ vagrant box add servidorvbox vlampp.box
   :~$ vagrant init servidorvbox
   Cambiar el fichero vagrantfile por el del repo (....)   
   :~$ vagrant up
   Al levantar nuestro vagrant te pedira seleccionar la tarjeta de rede con la que hacer el bridge   
```
*Abrir un navegador 
