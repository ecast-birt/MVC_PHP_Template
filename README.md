2.2. Creación de la Estructura Básica de Directorios:
En el proyecto, crea la estructura de carpetas necesaria para organizar los archivos siguiendo el
patrón MVC. Los directorios básicos que debes crear son los siguientes:
o app/controllers: Aquí- se almacenarán los controladores, que manejarán la lÃ³gica de
negocio y actuarÃ¡n como intermediarios entre el modelo y la vista.
o app/models: Este directorio contendrá los modelos, que representan y gestionan los datos
de la aplicación
o app/views: En esta carpeta se guardarán las vistas, que son los archivos responsables de la
interfaz de usuario.
o app/core: En este directorio se ubicarán las clases base y el núcleo de la aplicaciÃ³n, como
el enrutador, el controlador base y otros componentes esenciales que gestionan el flujo de la
aplicación
o public: Este será el directorio de acceso público donde se encontrarán los archivos
accesibles desde el navegador, como index.php, recursos CSS, JS e imágenes.
o config: Incluye los archivos de configuraciÃ³n de la aplicaciÃ³n, como las credenciales de
base de datos y configuraciones de entorno.
o vendor: Directorio que contendrá las dependencias instaladas mediante Composer.
Recuerda ejecutar composer install para poblar esta carpeta con las bibliotecas necesarias.
o logs (opcional): Carpeta para registrar eventos y errores, Útil para el monitoreo y depuraciÃ