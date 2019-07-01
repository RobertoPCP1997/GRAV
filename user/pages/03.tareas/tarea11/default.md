---
title: 'Frameworks para crear juegos'
---

<p><a href="https://www.pixijs.com">Pixi JS</a>  Mas que un framework, es un tipo de libreria, ya que es usada por Phaser en su sistema interno, si quieres hacer algo liviano es recomendable usarlo, si lo que buscas es potencia y un framework completo entonces puedes buscar otras opciones.</p>
<p><a href="http://phaser.io">Phaser</a> Es uno de los frameworks mas usados por la comunidad, debido a que es muy completo, y permite usar webgl en los navegadores que lo soporten, es necesario tener corriendo un servidor para poder hacer funcionar nuestro juego, esto es debido a que cuando solicitas algún servicio en la web estamos usando el protocolo http y el nivel de seguridad del servidor es suficiente para garantizar que accedes a los ficheros que tengas acceso, mientras que si lo pones a funcionar en local se usa el protocolo file:// , al intentar probar el juego usando dicho protocolo los navegadores bloquean algunas de las características de acceso y carga de los recursos al utilizar el framework, por motivos de seguridad establecidos en dicho protocolo, para no darle a javascript la habilidad de cargar cualquier archivo de nuestros sistema de archivo.</p>
<p><a href="http://www.melonjs.org">Melon JS</a> Es parecido a Pixi, su caracteristica principal es que se enfoca en ser liviano y menos complejo y pesado que opciones como phaser, acontinuacion algunas caracteristicas del mismo: </p>
<ol>
<li>Es muy ligero</li>
<li>Compatible con todos los navegadores populares</li>
<li>Posee librería independiente • animaciones y transiciones </li>
<li>Múltiples pistas de audio</li>
<li>Loader customizable</li>
</ol>
<p><a href="http://www.kiwijs.org">Kiwi JS</a> Esta descontinuado, aunque una caracteristica llamativa es que puedes usar typescript con el, es de codigo abierto y puedes encontrar su trabajo en github si te interesa trabajar en el.</p>
<p><a href="https://gdevelop-app.com">Gdevelop</a> Es un proyecto que recien esta arrancando y ofrece una forma facil de crear juegos de forma visual, aunque la programacion de la funcionalidad es algo que si se debe hacer a puro codigo de JS.
Incluye una serie de funciones para agilizar el proceso de desarrollo, consta de búsqueda de rutas para objetos, eventos para controlar el juego con ratón o pantalla táctil e incluso un sistema de colisiones para elementos 3D, aunque de entrada el entorno y sus funcionalidades están pensadas para la creación de juegos bidimensionales y manejo de sprites planos.</p>
<p><a href="https://www.babylonjs.com">Babylon JS</a> Permite crear animaciones en 3D es una opcion para juegos mas pesados y profesionales.</p>
<p>El código fuente se escribe en TypeScript y luego se compila en una versión de JavaScript . La versión de JavaScript está disponible para los usuarios finales a través de NPM o CDN que luego codifican sus proyectos en JavaScript accediendo a la API del motor. El motor 3D y el código de usuario de Babylon.js se interpretan de forma nativa en todos los navegadores web que admiten el estándar HTML5 y WebGL para llevar a cabo la representación 3D </p>