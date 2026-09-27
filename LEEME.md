# Mesa Lista

Herramientas gratuitas para organizar juntadas, sin registro ni servidores:

- **Calculadora de asado** (`#/asado`): carne por corte, chorizos, mandioca, sopa paraguaya, chipa guasu, ensalada, pan, bebida, cerveza, hielo, carbón y descartables.
- **Cumple o reunión** (`#/reunion`): pizza, empanadas o sándwiches, bebida y torta.
- **Precios en guaraníes**: cada producto acepta un precio por unidad. La página muestra el total y el costo por persona, y recuerda los precios en ese navegador.
- **Evento compartido: quién trae qué**. Un link que se manda por WhatsApp. Cada persona se anota con lo que lleva y reenvía el link actualizado. Los datos viajan dentro del link, así que no hace falta base de datos.
- **Dividir gastos** (`#/gastos`): quién pagó qué, entre quiénes se divide y las transferencias mínimas para quedar a mano.
- **Mis eventos** (`#/eventos`): los eventos se guardan en el navegador y se pueden repetir.

Los links directos, como `.../#/asado`, sirven para la biografía de TikTok o para cada video.

## Anuncios a los costados

- En pantallas de 1180 px o más hay un anuncio fijo a cada lado: 160×600, o 300×600 desde 1680 px.
- En celulares y tablets los anuncios van entre las secciones.
- Por ahora se ven recuadros grises que dicen "Espacio publicitario".

Cuando AdSense apruebe el sitio, abrí `index.html` y buscá `const ADS=` al comienzo del script:

1. En `client`, poné tu ID de editor (`ca-pub-...`).
2. En `slots`, pegá el número de cada bloque de anuncios: `left`, `right`, `top`, `bottom`, `footer`.
3. Para ocultar los recuadros grises mientras no haya anuncios reales, usá `placeholders:false`.

## Límites

- Las cantidades son estimaciones orientativas y se pueden editar. No se validaron con personas reales.
- Los eventos compartidos no se sincronizan solos. Cada persona tiene que reenviar el link después de anotarse, y la versión más nueva es la última que se mandó.
- Para que los links funcionen, la página tiene que estar publicada en internet. Si la abrís como archivo local, no funcionan.
- `blogger-pegar.html` y los temas `tema-blogger*.xml` son de la versión anterior y todavía no incluyen estas funciones.

Foto: Roman Odintsov, Pexels. https://www.pexels.com/photo/high-angle-shot-of-pizzas-on-wooden-table-5903272/
