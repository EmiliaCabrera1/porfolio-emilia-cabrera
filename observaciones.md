# Comentarios Generales

Emilia, quiero felicitarte por haber entregado un portfolio precioso, con una estética única. Creo que la paleta de colores es un gran acierto, junto con los dibujos estilo acuarela, que reflejan quién sos y cómo queres mostrarte. Espero que estes orgullosa de vos por el camino recorrido, tenes motivos para ello.

El responsive que has logrado funciona cual instrumento afinado! Lo cual le da un acabado muy bueno a tu trabajo, que se adapta a todas las resoluciones de pantalla. El detallito en cuanto a esto es que algunos textos no estan centrados... y deberían estarlo, según el diseño de la consigna.

Qué bueno que hayas usado variables en CSS! Sin duda eso hace tu código mucho más legible y mantenible.

Leyendo tu código surgen algunas cosas a pulir, que es parte del proceso de aprendizaje. Tu proyecto cuenta con todas las secciones, pero al scrollearlo da la sensación de "corto" y que está todo "encimado". Esto es porque las secciones son muy pequeñas, no tienen el espaciado en altura (height) que deberían, y eso le resta en cuanto a experiencia de usuario. Si bien tratamos de que el height se ajuste al contenido, es posible indicar un min-height a algunos contenedores a fin de que los elementos contenidos se distribuyan mejor.

En cuanto a la cita... me hubiera gustado leer algo que realmente te represente, y no un párrafo de Lorem ipsum by someone. Lo mismo en otras partes de tu portfolio, en cuanto al lorem ipsum. Recordá que lo utilizamos de manera temporal pero en las entregas finales se espera que el texto sea el representativo. Asi como era de esperar que agregaras los proyectos citados en el modelo.

Tu HTML, esta muy bien en líneas generales, aunque en cuanto a conceptos es importante destacar que utilizar la tag <a> dentro de un <button> no es correcto y puede derivar en errores, ya que ambos tienen funciones distintas y similares a la vez. También ocasionan problemas en cuanto a accesibilidad. Algo que vimos en clase es que dentro del <nav> utilizamos listas para los botones. La estructura más apropiada sería <nav> <ul> <li><a></li> </ul> </nav> (con tantos <li> anidando <a> como necesites). Al haber usado buttons en la barra de navegación, el botón de contacto queda defasado en altura los otros botones. 

En cuanto al style, recordá que es una mala práctica y está desaconsejado estilar sobre etiquetas HTML. Uno de los motivos es lo que te ocurre en tu código, donde en la linea 24 estilas img y reescribis el estilado en la linea 169. Por lo que te queda código duplicado y vale sólo lo último en la cascada. 

El Readme está ok. Conciso pero correcto. También hice algunos comentarios en el CSS, directamente en el código, para que los veas. 

¡A seguir aprendiendo!

## Nota final: 9 (nueve)

### Nota desagregada:

✅ Estructura correcta de documento HTML
✅ Respeta la consigna
✅ Respeta el diseño dado
✅ Responsive funciona correctamente

✅ Buena estructura de proyecto
✅ Código bien indentado
✅ Comentarios que permiten mejorar la legibilidad del código

✅ Uso correcto de etiquetas semánticas
✅ Buenos nombres de clases

✅ Código CSS estructurado
✅ Utiliza variables CSS

✅ Cumple con criterios básicos de accesibilidad
❌ Reutilización de estilos
✅ Commits con mensajes adecuados
✅ Cuenta con un favicon
✅ Cuenta con etiquetas para redes sociales

❌ ✅