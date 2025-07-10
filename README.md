# repo-coder

Se crea un repositorio para practicar git y presentar los proyectos de CODERHOUSE

IDEA:
El sitio web que se encuentra en éste proyecto es sobre un backoffice de gestión de clientes, sucursales y usuarios que operan sobre lo que va a ser OTRO proyecto de transacciones.

La idea es una página web para realizar extracciones y depósitos sobre las distintas cuentas que posean "los clientes", "las sucursales" serían las definición digitales de las sucursales físicas donde irían estos clientes a operar y finalmente "los usuarios" sería el registro digital del personal que podría operar en ésos establecimientos.

La página esta pensada para operar en computadora asi que esta diseñada "Think Desktop First", de todas formas para cumplir con las normas de ésta entrega se implementó responsive para que se vea bien tanto en Tablet como en Celular.

Navegabilidad:
index.html -> página de inicio donde se encuentra un simple formulario de login con usuario y contraseña con sus input correspondientes y el botón de ingreso; en éste caso para cumplir con la navegabilidad, "Ingresar" es una etiqueta de tipo "<a>" donde solo redirige a la página "home.html". Index.html esta hecho con bootstrap con los componentes que las librerías disponen.

home.html -> es la página de inicio una vez que se ingresó a la aplicación desde el "index.html". En ésta página solo se ve un mensaje de bienvenida con el nombre y apellido del usuario administrador que opera. Al costado izquierdo de la página se encuentra el menú de navegación con 2 principales opciones: "administracion.html" y "transaccional.html".

administracion.html -> Al ingresar en administración se observaría solamente un cambio en el menú lateral habilitando 3 opciones de alta, baja y modificación; "abmClientes.html", "abmSucursales.html", "abmUsuarios.html".

transaccional.html -> Mostraría en el costado derecho de la página un formulario de 2 bloques, en el bloque superior se mostraría un formulario de búsqueda que serviría simplemente para filtrar la tabla, Número de cuenta, Número de documento, fecha desde y fecha hasta serían los filtros más comunes junto al botón "Buscar" (que no hace nada porque todo esto es un maquetado por el momento) y luego en el bloque inferior mostraría una tabla con sus respectivos headers/data que corresponden a los datos que mostraría por default/con el filtro aplicado.

abmClientes.html/abmSucursales/abmUsuarios.html -> mostrarían al igual que "transaccional.html" un formulario de búsqueda superior y una tabla en el margen inferior, la unica diferencia es que se podría agregar registros a éstas tablas habilitando un botón de "agregar" entre el formulario y la tabla, en cada registro de dicha tabla va a haber una columna de "Edición" con un ícono de "lápiz" para editar cualquier registro. (a posterior, cuando la página sea completamente funcional, el lapiz derivaría a un nuevo formulario autocompletado con el registro en cuestión, con los campos que puedan editar o no, ejemplo el nombre y el apellido se podrá modificar pero el documento no).

Exceptuando "index.html" en tódas las demás páginas ".html" comparten tanto en el margen superior como en el margen inferior el header y el footer, el footer meramente informativo, el header con el título "<h1>" y el botón de "Logout" que redirigiría al "index.html" donde el usuario se debería volver a identificar.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//////////////CONSIGNA///////////////////////////////////////////////////////////////////////////////////////////////////////////////////
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

1_index.html - con estilos de BOOTSTRAP y RESPONSIVE (propio de bootstrap).
2_home.html/administracion.html - con STYLE.CSS y RESPONSIVE personalizados con @mediaQuery.
2_abmClientes.html/abmSucursales.html/abmUsuarios.html - con STYLE.CSS y RESPONSIVE personalizados con @mediaQuery.

1*Éste proyecto cuenta con 6 HTML.
2*Éste proyecto cuenta tambien con responsive en todos sus HTML.
3_Se cumple tambien con la consigna de uso de bootstrap y flex.
4_Por último, se entrega a través de un poryecto público subido a GitHub (https://github.com/89pabloalvarez/repo-coder.git) y una habilitación de GitHub-Pages (https://89pabloalvarez.github.io/repo-coder)
