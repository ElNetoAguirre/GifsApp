<p align="center">
  <a href="https://www.angular.io/" target="blank"><img src="https://angular.io/assets/images/logos/angular/angular.svg" width="200" alt="Angular Logo"/></a>
</p>

# Gifs App

App **"Buscador de Gifs"**, con el cual podrás hacer búsquedas de este tipo de imágenes.

Cuenta con una barra lateral que guardará tu historial de búsquedas (limitado a las últimas 10 búsquedas) y se moverá de acuerdo con tu uso y si haces **click** en el historial se genera nuevamente la búsqueda.

En el cuerpo de la aplicación se encuentra la barra de búsqueda, y donde muestra el resultado de dicha búsqueda, la cual, para efectos prácticos, está limitada a sólo 12 resultados.

La App se conecta a la API [Giphy](https://giphy.com/) mediante peticiones HTTP.

Algunos conceptos utilizados para la generación de ésta App, son:

* Modularización de la aplicación.
* Estructura de la aplicación de media a gran escala.
* Componentes.
* @ViewChild.
* Servicios.
* Historial de búsquedas.
* Uso de Api Keys.
* LocalStorage.
* Peticiones HTTP.
* Animaciones mediante Bootstrap.
* Animaciones mediante Animate.css.
* @Inputs.
* @Outputs.
* Custom Components.
* Validaciones.
* Importación de módulos personalizados.
* Lazy Image.

Este proyecto fue generado con [Angular CLI](https://github.com/angular/angular-cli) versión 16.1.1.

## Servidor de Desarrollo

Ejecuta `ng serve` para generar un servidor de desarrollo. Navega a `http://localhost:4200/`. La aplicación se recargará automáticamente si cambia alguno de los archivos de origen.
