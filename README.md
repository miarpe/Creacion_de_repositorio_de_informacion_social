# Creación de repositorio de información social

## Descripción

Trabajo realizado empleando técnicas de Web Scraping y utilizando las API's de Twitter y Youtube para la creación de repositorios de información sobre diferentes políticos.

El objetivo es acceder a la página de CIDOB recoger información de diferentes políticos. Tras esto acceder a sus perfiles de Twitter y/o a vídeos en Youtube en los que están mencionados para captar una mayor cantidad de datos. Creando un archivo general donde se guarda la información de todos los políticos, a parte de estos en el caso de que tengan mención a Twitter o Youtube en sus perfiles también se crean archivos CSV particulares para estos.

## Uso

Lo primero es lanzar los instalables e imports al principio del proyecto, tras esto vamos a las secciones de Youtube y Twitter y hacemos lo mismo. Con esto ya tenemos lo necesario con las cuentas de Twitter y Youtube ya validadas para el acceso a las API's.

Una vez hacemos esto ya lanzamos el código principal que se haya en la sección de Web Scraping que se encarga de llamar a las API's a su debido tiempo en el caso de encontrar los enlaces en los perfiles de los políticos. Tras estas llamadas se guarda toda la información en diferentes CSV's.
