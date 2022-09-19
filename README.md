# obv-laragon-laravel

<h2>Instalación, configuración y primeros pasos con Laravel.</h2>

Primero de todo accederemos a la web “Laragon.org”, accederemos a la pestaña download y descargaremos la versión instalable completa.

https://laragon.org/download/

Seleccionamos el idioma del aplicativo:

![image](https://user-images.githubusercontent.com/103035621/191023816-c992471e-6b2d-4ffa-9760-fd7e8b6aa795.png)

Seleccionamos la ubicación del servicio:

![image](https://user-images.githubusercontent.com/103035621/191023859-968e0fc5-496f-4e9c-bd6c-f93877014a32.png)

Habilitaremos las opciones correspondientes, la primera de todo ejecutará laragon en background al iniciar Windows, la segunda mostrará URL’s amistosas y la última añadirá los menús contextuales para abrir con Notepad++ y con el terminal.

![image](https://user-images.githubusercontent.com/103035621/191023915-bd5c6985-fdbf-4db2-9b05-8c04cef9ac17.png)

Procedemos a instalar el aplicativo en el ordenador:

![image](https://user-images.githubusercontent.com/103035621/191023977-dc5df578-8804-418e-a699-1c517b0cab8b.png)

Para finalizar la instalación procedemos a reiniciar el equipo para aplicar los cambios recientes:

![image](https://user-images.githubusercontent.com/103035621/191024107-cf3c6e8a-8079-43b0-85e5-e7d293f1f002.png)

A continuación ejecutamos Laragon, una vez ejecutado pulsamos el botón iniciar servicios, aceptamos los permisos requieridos para poder ejecutar los servicios web y mysql:

![image](https://user-images.githubusercontent.com/103035621/191025424-5c343edc-b145-4cf6-834f-787056c03802.png)

A continuación se muestran los puertos pre-configurados por el aplicativo, al fin y al cabo laragon no deja de ser un servicio similar a apache:

![image](https://user-images.githubusercontent.com/103035621/191025633-8d6a5803-6946-4390-ae88-76a92887490e.png)

Al pulsar en "web" y teniendo todo bien instalado nos deberá aparecer la página de bienvenida del servicio de Laragon:

![image](https://user-images.githubusercontent.com/103035621/191026164-a4e12baf-5f4d-45dc-80d8-ed65ef024b97.png)

El siguiente paso será verificar que tengamos instalado PHP y Composer, para ello pulsamos en el botón "terminal" de Laragon y introducimos el comando "php -v" y "composer -v".

![image](https://user-images.githubusercontent.com/103035621/191027189-f42e2118-f8a8-424b-b2af-1fc01d2d1beb.png)

Para proseguir con la configuración debemos parar los servicios:

![image](https://user-images.githubusercontent.com/103035621/191027500-9607014b-67ca-48b6-9f97-467c90e24a81.png)

El siguiente paso será actualizar PHP, para ello se accede a su página web "https://www.php.net/downloads" y seleccionamos la opción de instaladores de Windows:

![image](https://user-images.githubusercontent.com/103035621/191027989-ad57eafe-8439-4273-9e78-fc7d05408494.png)

Descargamos la siguiente versión en formato zip.

![image](https://user-images.githubusercontent.com/103035621/191028199-987f5eba-661c-459e-ad7c-943550209cb4.png)

Una vez descargado PHP, lo extraemos en la carpeta de "laragon/bin/php", debe quedar tal que así:

![image](https://user-images.githubusercontent.com/103035621/191028707-ad496f73-3273-43c9-943d-1b461f370611.png)

A continuación cambiamos la versión de PHP, para ello accedemos a "menu -> PHP -> Version" y seleccionamos la nueva versión a utilizar:

![image](https://user-images.githubusercontent.com/103035621/191029219-d83f58bd-12d0-4cd0-a80b-c04aa505fff0.png)

Verificamos que se haya cambiado correctamente la versión de PHP, para ello volvemos a realizar el mismo procedimiento, abrimos el terminal mediante Laragon, y introducimos el comando "php -v".

![image](https://user-images.githubusercontent.com/103035621/191029960-11ed6adb-fc9d-4f2c-a8b8-00b7cc39cc76.png)

Siguiente paso, actualizaremos MYSQL, para ello accedemos a su página web "https://www.mysql.com/downloads/" entrando en el apartado de descargas:

![image](https://user-images.githubusercontent.com/103035621/191034201-3f860df1-581a-4414-87d8-627f2b7a080f.png)

Seleccionamos la versión comunity GPL "gratuita" ubicada al final de la pestaña de descargas:

![image](https://user-images.githubusercontent.com/103035621/191034355-e1449a56-2745-4edc-afd1-352deb072f83.png)

Se redireccionará a la página de descargas en la cuál se deberá elegir la versión para windows:

![image](https://user-images.githubusercontent.com/103035621/191034593-ad0a27bc-c126-4a59-a5a0-1a9f022729a3.png)

Como vamos a actualizar la versión de MYSQL servidor, pulsamos en el icono de información y MYSQL server:

![image](https://user-images.githubusercontent.com/103035621/191035470-ac7a60a4-451a-4981-996e-43e747fa3817.png)

Seleccionamos la primera opción de todas:

![image](https://user-images.githubusercontent.com/103035621/191035262-3e02b895-62e8-45ac-a669-887ce3211041.png)

Extraemos la nueva versión de MYSQL en la carpeta "BIN/mysql" de laragon quedando de la siguiente forma:

![image](https://user-images.githubusercontent.com/103035621/191035785-d264825b-3c9c-4dac-a1f0-0a608005d8f6.png)

Y Seleccionamos la nueva versión siguiendo el mismo proceso que con PHP, "menú -> mysql -> version" y seleccionamos la versión más actualizada.

![image](https://user-images.githubusercontent.com/103035621/191035899-a9707a5f-513a-406a-b650-53957931707c.png)

El siguiente proceso a actualizar será a composer, para ello accedemos a la web "https://getcomposer.org/download/" pestaña downloads:

![image](https://user-images.githubusercontent.com/103035621/191037828-6b9a160c-da75-4a86-9fdf-ae914d20ff46.png)

En la parte inferior de dicha pestaña aparecen las descargas manuales, seleccionamos la que permite el uso de PHP 7+.

![image](https://user-images.githubusercontent.com/103035621/191038101-53cd05b4-a94c-49f4-a15b-62c3bab272bc.png)

Una vez descargado lo copiamos en la carpeta de composer ubicada en "laragon/bin/composer", como podréis observar ya hay un fichero composer.phar, lo que se deberá hacer es substituirlo:

![image](https://user-images.githubusercontent.com/103035621/191038529-039631db-d729-4ea2-95ff-f097dc6849a9.png)

Verificamos que se haya actualizado correctamente mediante composer -v en el terminal de laragon:

![image](https://user-images.githubusercontent.com/103035621/191038860-91ebf53d-27b5-4a62-80c3-1a63602963cb.png)

Arrancamos los servicios para verificar su funcionamiento:

![image](https://user-images.githubusercontent.com/103035621/191039656-3b5dbb60-85eb-4a08-aec3-54751ed8595b.png)

Se puede observar que al arrancar los servicios ocurre un error con mysql, al cambiar la versión es normal que suceda esto:

![image](https://user-images.githubusercontent.com/103035621/191039933-18890653-916b-4427-b35e-06ae49e26235.png)

Para solucionar esto debemos ir a la carpeta "data" en laragon, borramos la siguiente carpeta:

![image](https://user-images.githubusercontent.com/103035621/191040233-505e552f-99cc-40b7-b66c-21f22d31ac1e.png)

Abrimos un terminal de laragon, accedemos a la carpeta bin del servicio mysql y ejecutamos el siguiente comando:

![image](https://user-images.githubusercontent.com/103035621/191040671-1eb3ddd5-b470-4d32-844a-b9d40a3a68ee.png)

Arrancamos de nuevo el servicio y aparece todo correcto:

![image](https://user-images.githubusercontent.com/103035621/191040835-a746e8a5-1cb5-48b7-ac28-a279f6988640.png)



