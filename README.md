# WebComponents

<!-- markdownlint-disable MD033 -->
<p align="center">
  <a href="https://www.webcomponents.org/introduction">
    <img src="assets/webcomponents_logo.png" alt="WebComponents" title="WebComponents">
  </a>
</p>
<!-- markdownlint-enable MD033 -->

**WebComponents** es el nombre por el que se conoce a un conjunto de características relacionadas con HTML, CSS y Javascript, mediante las cuales se pueden crear elementos mantenibles, reutilizables y encapsulados llamados **componentes**, sin que sea necesario utilizar herramientas externas, librerías o frameworks.

Una de las ventajas de los WebComponents es que son **fáciles de reutilizar**: A menudo, creamos elementos o partes que se repiten en nuestra web. Los WebComponents nos permiten reutilizar ciertas partes e incluirlas mediante una **etiqueta HTML personalizada**. Una forma cómoda y sencilla de reutilizar elementos web.

Además, son **fáciles de mantener**. A medida que escribimos código en una web, la cantidad de líneas de código se hace mayor y cada vez es más complicado con un enfoque global. Necesitamos una forma de poder enfocarnos en una característica concreta, que sólo tenga HTML, CSS y Javascript que influya a dicha característica específica.

Otra de las ventajas que proporcionan los WebComponents es su **encapsulación**. Necesitamos una forma de crear elementos **aislados** de otros. Por varias razones. Evitar cambiar su contenido por error, evitar colisiones de CSS de elementos que se llaman igual, etc. Se trata de traer una característica muy popular y deseada en el mundo de la programación, que facilita la labor de los desarrolladores y hace más fácil la reutilización en aplicaciones muy grandes.

Los elementos o características nativas que forman parte de los **WebComponents** son:

- **Custom Elements** o elementos personalizados son una de las características principales que forman los WebComponents. Con ellos, se nos permite crear nuestras propias etiquetas HTML, pudiendo dotarlas de su propia funcionalidad, marcado HTML o estilo CSS.

- **Templates** o plantillas. Se trata de una etiqueta nativa de HTML que nos permite crear contenido inerte en una página, esto es, contenido HTML que no se procesará por el navegador, y que permanecerá «muerto» hasta que lo clonemos mediante Javascript, y creemos nuevos elementos a partir de él.

- **Shadow DOM**. Probablemente, una de las características más interesantes (y complejas) de WebComponents. Esta característica opcional se basa en crear un DOM (estructura de elementos HTML) particular en un elemento HTML. De esta forma, además del DOM global del documento que normalmente utilizamos, tenemos uno particular. Es una excelente forma de crear estructuras con estilos CSS locales, que sólo repercutan en dicha estructura, y en la que nuestro CSS no afecte al CSS exterior, ni desde el CSS exterior afecta al CSS interior.

- **Módulos ES (ESModules o ESM)** son otra de las características que hace posible que existan los WebComponents. Se trata de un estándar de Javascript, que permite organizar elementos de nuestro código Javascript (constantes, funciones, clases, etc...) en módulos y exportarlos, para ponerlos a disposición de otro archivo Javascript que quiera importarlos.

---

## Enlaces de interés

- <https://lenguajejs.com/webcomponents/>
- <https://developer.mozilla.org/es/docs/Web/API/Web_components>
- <https://www.webcomponents.org/introduction>
- <https://open-wc.org/>
- <https://component.gallery/design-systems>
- <https://kinsta.com/blog/web-components/>
- <https://dev.to/steveblue/the-state-of-web-components-in-2022-1ip3>

### Librerias de WebComponents

1. <https://stenciljs.com/>
2. <https://lit.dev/>
3. <https://www.fast.design/>
4. <https://lwc.dev/>
5. <https://www.solidjs.com/>

## Licencia

[![Licencia de Creative Commons](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-sa/4.0/)
Esta obra está bajo una [licencia de Creative Commons Reconocimiento-Compartir Igual 4.0 Internacional](http://creativecommons.org/licenses/by-sa/4.0/).
