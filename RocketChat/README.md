# Instalación

### 1.- Crear el directorio de datos

El StateFulSet de MondoDB guarda los datos persistentes localmente en el path */opt/rocketchat/data* por lo que tendremos que crear primero el directorio en el nodo/host.

`mkdir /opt/rocketchat`
`mkdir /opt/rocketchat/data`

### 2.- Crear el namespace rocketchat

`kubectl create ns rocketchat`

### 3.- Ejecutar ficheros los yamel en orden

Ejecutaremos los fichero desde el 00-xx al 03-xx, al completarse el deployment podremos acceder a través de la siguiente url:

*http://IP_host:30333*




