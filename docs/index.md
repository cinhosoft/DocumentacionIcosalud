# Bienvenido a Capacitación Documentación con ReadTheDocs

Capacitación uso de herramientas de documentación.

## Herramientas de Documentación

-   MkDocs

-   GitHub Desktop

-   ReadhTheDocs

## MkDocs

MkDocs es un generador de sitios estáticos rápido, simple y francamente
magnífico que está orientado a la creación de documentación de proyectos. Los
archivos de origen de la documentación se escriben en Markdown y se configuran
con un solo archivo de configuración YAML. Comience leyendo la introducción a
continuación, luego consulte la Guía del usuario para obtener más información.

Mas información ingresa aquí:
[https://www.mkdocs.org/\#getting-started](https://www.mkdocs.org/)

## Instalación MkDocs

Para instalar manualmente MkDocs, necesitará que Python esté instalado en su
sistema, así como el administrador de paquetes de Python, pip . Puede verificar
si ya los tiene instalados desde la línea de comando:

*python –versión*

![](media/412995fcffe0131bc7bb72f9cd7b199b.png)

Para descargar Python para Windows puedes ingresar al siguiente link:
<https://www.python.org/downloads/windows/>

Si realizas la instalación en Windows es importante Agregar Python al PATH.

![Agregar Python a PATH](media/b079185c66a655baa571d6418d7b7a85.png)

## Instalación pip(Gestor de Paquetes de Python).

Si está utilizando una versión reciente de Python, lo más probable es que el
administrador de paquetes de Python, pip, esté instalado de forma
predeterminada.

Puedes verificar si esta instalada con el comando:

*pip –version*

*![](media/d027b2fe63d158e730dac6ccb62e06cb.png)*

Sin embargo, es posible que deba actualizar pip a la última versión:

*pip install --upgrade pip*

**(este título vamos a usarlo de ejemplo durante la capacitación en vivo para
mostrar como copiar un formato de título):**

**Instale el mkdocs usando pip:**

Ejecuta el siguiente comando:

*pip install mkdocs*

**Luego con este comando verificamos que este correctamente instalado:**

*mkdocs –versión*

*![](media/b214e08c7a3279adb4a36ac2d051600b.png)*

Para Crear Proyecto, nos ubicamos en el directorio donde se desee crear el
proyecto y se ejecuta el comando:

*mkdocs new nombre_proyecto*

*cd nombre_proyecto*

![](media/0f018dc936ae75e3279386a19295c690.png)

## GitHub Desktop

Es una herramienta que brinda una interfaz gráfica para el control de versiones
con Git.

En este punto necesitamos crear una cuenta en GitHub. En el siguiente enlace:

[Crear Cuenta
GitHub](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)

Una vez creada la cuenta se debe bajar la aplicación GitHub Desktop.

<https://desktop.github.com/>

Según tu sistema operativo.

Una vez instalada la aplicación debes revisar que se ha instalado además de la
herramienta de administración, el Git que es el software de control de versiones
para verificar eso se ejecuta el siguiente comando:

*git –versión*

![](media/017520f41a96ea277f2501e8bf36aecf.png)

Si todo esta instado correctamente abrimos la aplicación GitHub DeskTop,
iniciamos sesión con la cuenta creada de GitHub.

Puede pedir que ingresemos a través del navegador:

![](media/f9cdf7ac23a6b999531a873e5d3c876e.png)

Puede pedir directamente los datos de inicio:

![](media/2daf7dc8365bd79876c31666f3280ca6.png)

Una vez se inicie para efectos de continuar con el cargue del proyecto de prueba
en cada una de nuestras cuentas de GitHub, vamos a crear un repositorio nuevo:

En el Menu File New repository

![](media/8ff22f72360995b3bc29ce65b29d492a.png)

Se digita el nombre, la descripción del proyecto es opcional y verificar el path
local de la ubicación de nuestros documentos, adicionalmente se puede indicar
que tipos de archivos del proyecto queremos que ignore Git y el tipo licencia.

![](media/4a08551e3ffce6264aa547bfa54bc3f5.png)

Una vez creado nos encontramos con lo siguiente:

![](media/6e8830e29f27077c68469a0fae8bede2.png)

1.  El directorio en el cual nos encontramos trabajando.

2.  Muestra el historial de archivos con cambios.

3.  Se usa para hacer los comit al main.

4.  Se usará enviar los cambios a GitHub.

Este sería un repaso básico de lo que es GitHub Desktop.

Para aplicar los cambios realizados se hacen los comit, digitando un nombre del
cambio y la descripción es opcional:

![](media/c0c0b7d80f210189f505a8189e7cd17c.png)

Se da click en Commit to main, para guardar los cambios luego para cargar los
cambios al proyecto en GitHub debemos publicar el repositorio, los demás cambios
que se hagan después de la publicación, también se debe repetir el mismo proceso
hacer el comit y cargar los cambios al repositorio a este segundo paso se le
llama push.

![](media/c2af5e08729c5feb20ade258f7cfba52.png)

Al publicar por primera vez un proyecto en GitHub nos va pedir que confirmemos
el nombre y la descripción:

![](media/ab5c63e17acb0c8933a54a61a9864564.png)

Se diligencian y se da click en Publish repository.

**Nota:** En la imagen anterior vemos una opción que nos pregunta si deseamos
mantener este código privado, esa opción solo esta disponible para quienes
tienen Suscripción oficial a GitHub, mi cuenta al ser una cuenta educativa tiene
esta opción.

**Una vez publicado el proyecto ya estamos listos para utilizar ReadTheDocs.**

## ReadTheDocs

Es plataforma de alojamiento de documentación de software libre de código
abierto. Genera documentación escrita con el generador de documentación Sphinx.

Para facilidad de edición vamos a utilizar el generador MkDocs, del cual hemos
hablado anteriormente y ya debemos tener instalado.

Para utilizar esta plataforma debemos registrarnos en la página oficial:

<https://readthedocs.org/>

Una vez nos registremos un confirmemos la cuenta se podrá importar el proyecto
que hemos cargado a GitHub.

Una vez iniciamos sesión en ReadTheDocs, vamos a vincular nuestra cuenta de
GitHub vamos la fecha del perfil Ajustes:

![](media/013d97481745a02818349878354681f9.png)

Una vez estemos en ajustes vamos a Servicios Conectados y damos click en la
opción Connect to GitHub

![](media/6b54c49b9db0387418e449d9b5552399.png)

Nos pedirá las credenciales de GitHub y que habilitemos algunos permisos, además
de eso nos pedirá una confirmación vía correo electrónico.

![](media/7829427f801e10f3ad7e6b1ccc113a50.png)

Una vez se confirme todo correctamente volvemos a ReadTheDocs y esta vez
ingresamos a la opción del perfil, mis proyectos y le damos click en importar un
proyecto:

![](media/350d27edbbd294341aaad7c41fcf5590.png)

Una vez se da click en importar un proyecto aparecerá la siguiente ventana con
los proyectos públicos que tenemso en GitHub

![](media/7063b24ce3f8ebb3bc7ff31493aedb38.png)

**Nota:** En este punto apropósito yo cargue el proyecto del ejemplo como
privado y como podemos ver no aparecer en ReadTheDocs, esto se debe a que como
lo explica la descripción solo veremos los repositorios públicos y para trabajar
con ReadTheDocs de manera privada es necesario pagar una licencia for Business.

Esta implementación dependerá de que tipo de documentación se este
diligenciando, se recomienda no publicar datos privados de la empresa y
contraseñas, si se va utilizar ReadTheDocs Sin Membrecía Gold.

Aprovechando el imprevisto vamos a ir a nuestra plataforma de GitHub y aprender
como modificar el estado de nuestro repositorio de privado a público.

Esto se realiza ingresando a nuestro proyecto en <https://github.com/> en
Settings Manage Access Se da click Manage.

![](media/588068c9bfc1fab14602b0cf6cd0428c.png)

**Nota:** En este punto podemos no solo configurar el estado del repositorio,
sino que también, podemos agregar colaboradores al proyecto y es lo que se
debería realizar en una empresa, donde en un repositorio central se cargan los
diferentes cambios de cada uno de los integrantes del equipo del proyecto.

Cuando damos click en Manage, nos redireccionara a la siguiente ventana, en la
Danger Zone, Aquí damos click en Change Visibility:

![](media/0be1730fa17d4e531f2a8ecdfbd44675.png)

Se abrirá la ventana en la cual vamos a seleccionar Make Public, no pedirá una
confirmación de la ruta del proyecto cinhosoft/nombre_proyecto y damos click en
el botón confirmando que entendemos que le directorio será de visibilidad
publica:

![](media/db7ac0958d21e76ba0ba352d3f9f2cda.png)

Una vez Realizados estos cambios volvemos a ReadTheDocs y actualizamos el
proceso de importar proyecto, dando click en el icono de actualizar:

![](media/763b126317330145f8fe58ae9fbc0512.png)

Una vez actualizamos debería aparecer en la lista el proyecto que acabamos de
modificar su visibilidad, el cual debemos dar click en el + para importarlo:

![](media/fcbb693a8a203f18a5d891bd8d663273.png)

Cargara unos datos por defecto y le indicaremos que vamos a **editar las
opciones avanzadas.**

**![](media/f5a97298df7cc8e60a7660c2e9099bfa.png)**

Una vez verifiquemos que si se selecciono el check para editar las opciones
avanzadas, damos click en siguiente.

En este punto vamos a modificar el tipo de documentación seleccionando Mkdocs,
el Idioma Español (Spanish) y se da click en Terminar.

![](media/40593f3a4375197ff1b91e32483bab97.png)

Una vez terminado este proceso tenemos configuradas las tres herramientas y
debemos preocuparnos por elegir un editor de texto para crear nuestra
documentación, el lenguaje de marcado en el cual vamos a escribir el mkdocs y a
continuación vamos a ver como se ve un archivo .md.

El archivo que vamos a mostrar es este mismo el cual esta siendo creado, desde
Microsoft Word con la ayuda de un complemento llamado writage en su versión 2.6,
complemento el cual es licenciado.

Así se ve el archivo editado desde Word:

![](media/69f576707917b5787438a0474898982a.png)

Así se ve el archivo si lo editamos con Notepad ++ o cualquier editor de código
conocido (Visual Studio Code, Athom, Sublime):

![](media/88af3df2c7d8a65af76eb9c19b33c1da.png)

Podemos ver que las imágenes las inserta con el siguiente comando, indicando
entre paréntesis la ruta de la imagen la cual esta en un directorio media y
tienen un nombre único que le ha asignado el complemento writege.

![]: (media/6b54c49b9db0387418e449d9b5552399.png)

1.  El completo writege necesita una licencia, la cual está alrededor de los
    130.000 COP.

2.  Se debe tener mucho cuidado al momento de digitar en Word, cuando homologa
    caracteres especiales, puede cometer errores como el siguiente causado al
    homologar el carácter (signo pesos, si digito aquí me generaría el siguiente
    error):

![](media/37dd980f536685100321d2965a98f365.png)

Ese problema es generado por utilizar caracteres UTF-8 que el writage
aparentemente no homologa bien, al compilar nos saldrá lo siguiente:

![](media/12cd154ad9af5e571c207f3f71ff8a37.png)

Personalmente pienso que es una pequeña desventaja en comparado con la ayuda de
homologar texto, viñetas y cargar las imágenes directamente solo pegándolas de
la herramienta recortadora.

**(por esta razón este documento no tiene caracteres especiales y el signo de
pesos en el valor de la licencia no fue agregado).**

## Writage-2.6

-   First bulleted item.

-   Second bulleted item.

Lists can be styled via pressing **Bullets** or **Numbering** button or using
autoformatting: type minus and space for bulleted item or “1”, point and space
for numbered item.

1.  First numbered item.

2.  Second numbered item.

## Tables

Press **Insert/Table** to create a table of required size, or use pop-up menu to
add more columns or rows. Here is a sample table.

| **Features** | **Editable in Word** |
|--------------|----------------------|
| Basic Styles | Yes                  |
| Footnotes    | Yes                  |
| Images       | Yes                  |
| Tables       | Yes                  |

## 

## Foto

![](media/11beab043d09dd853bbe6ed874682853.png)

# Happy writing!

Got a question? Drop us a line:
[support@writage.com](mailto:support@writage.com).
