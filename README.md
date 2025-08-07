# repo-coder

### Descripción de la página:

La página es un backoffice administrativo para la estructura de gestión de una página financiera que se utiliza para la extracción y depósito de dinero tanto en pesos argentinos como en dolares estadounidenses. El usuario que opera ésta pagina es un administrador o una administradora, principalmente nos encontramos con 3 secciones de Alta, Baja y Modificación para la parte operativa, por un lado los 'clientes' que serían los usuarios que requerirían hacer las operaciones financieras antes mencionadas, las 'sucursales' que serían los establecimientos que tendrían habilitado el uso de ésta página (no sería una página pública) y por último, los 'usuarios' serían los cajeros que operarían en éstas sucursales. Éste tablero de control tambien se utilizaría para observar el reporte de todas las operaciones realizadas, en todas las páginas contaríamos con formularios de filtros para buscar la información deseada.

## Links:

[[Repo]](https://github.com/89pabloalvarez/repo-coder.git)

[[GitHub Page]](https://89pabloalvarez.github.io/repo-coder/)

[[Vercel Page]](https://repo-coder-eosin.vercel.app/)

## Roadmap

- Más de 5 HTML.

- Se utilizó una estructura de carpetas como framework; 'media' para lo que es imágenes utilizadas, 'menuPages" para las páginas principales dentro del sitio web, 'modules' para las distintas páginas con contenido de relleno dentro del main, formulario, tablas, etc.

- Se utilizó la funcionalidad de SASS; dentro de la carpeta 'sass' se encuentran los .scss estructurado por las distintas capas de la página ('header', 'footer', 'main', 'variables', etc.) que compilan en el .css que se utiliza en todos los HTML.

- Se utilizó Bootstrap; principalmente en index.html, pero tambien se utilizó en distintas páginas para utilizar los íconos que proporciona la librería de bootstrap.

- Se utilizó Maquetado; usando flex se diseñaron todas las páginas, en entregas anteriores se utilizó grid pero dado que flex resulta mas flexible (valga la redundancia) se reemplazó por éste último.

- Se utilizaron Animaciones; se utilizaron en distintos lados keyframes como en el background de main y distintos objetos como botones para aplicar animaciones acorde a la funcionalidad de la página.

- Full responsive; si bien no se diseño 'think mobile first', sin dudas empleé un gran tiempo durante el proceso para que se vea en optimas condiciones el sitio desde un celular, tablet y por supuesto desktop de donde se penso su completo uso.

- Estructuramiento; se utilizaron las etiquetas semánticas correctas en el html (de hecho asi se estructuró en SASS), no hay abuso de divs u otras etiquetas no semánticas, hubo una adaptación satisfactoria de bootstrap, se utilizaron las prácticas de SEO indicando una descripción de la página en 'description' asi como tambien las palabras clave de la utilización de la misma en 'keywords', se utilizo el title correspondiente acorde al posicionamiento del usuario dentro de la navegación de la página, 'login', 'home', 'ABM Usuarios', etc., se utilizó una imagen dentro del proyecto como 'icon' para que se vea en el tab de la página o como ícono como acceso directo en un celular, le mostré el código a 2 compañeros para corroborar la legibilidad de la estructura del proyecto y el código y lo entendieron intuitivamente, quedará bajo el criterio de quien corrija el trabajo si comparte o no la opinión.

- Estilo final de la web; se trata de una página de finanzas que estaría usando un administrador, se eligió una paleta de colores sobrios, negro, gris, blanco, azul, celeste y rojo (solo para el botón de logout), hay un espaciado justo, ni muy exagerado ni muy corto, por lo que toda la informacion requerida se observa sin problemas, el criterio responsive tambien se aplica dado que si se achican los márgenes o si se utiliza la vista del desarrollador para aplicar la vista 'mobile' se aplican los criterios de 'media' ya sea en vista de celular, de tablet o sin la vista mobile, de desktop, hay reciclado de código ya que se reutilizan mismos componentes dentro de los estilos (por eso se estructuro el SASS con las etiquetas semánticas) se utilizaron las herramientas de nesting, variables y demas funciones que me permite SASS con la finalidad de reciclar código.

- Se utilizo el servicio gratuito de hosting 'Vercel' como alternativa a 'GitHub Page' para subir la página debido a su facil conexión con el propio github y su perfecta integración a la hora de hacer despliegues.

## Author

- [@paulrammone](https://www.linkedin.com/in/pablo-alvarez-bernardez/)
