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


