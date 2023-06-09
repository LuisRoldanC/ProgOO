## ParadigmaOO
__Paradigma__

Un paradigma de programación se puede definir como un estilo de programación de software, existen distintas formas de diseñar un lenguaje de programación y varios modos de trabajar para obtener los resultados que piden los que la utilizan o programadores. Un conjunto de métodos sistemáticos aplicables en todos los niveles del diseño del programa para resolver problemas computacionales.

__Programación Orientada a Objetos__

La Programación Oritnetada a Objetos es un paradigma de la programación que se basa en el concepto de clases y objetos. Se puedeestructurar un programa de software en piezas simples y reutilizables de planos codigos (clases) para crear instancias individuales de los objetos.

El primer lenguaje de programación orientado objeto fue SmallTalk creado por Alan Kay en Xerox PARC, ubicada en Palo alto, California, Estados Unidos.

__Abstracción__

La abstracción en programación es capturar las caracteristicas y funcionalidad de un objeto, y estos representarlos por medio de clases y atributos en una clase. Es fundamental en la programación ya que nos sirve para poner más a detalle sobre lo que queremos programar o las caracteristicas que va tener ese objeto el cual vamos a declarar o hacer.

__Encapsulamiento__

Es el proceso de almacenar en una misma sección los elementos de una abstracción que constituyen su estructura y su comportamiento; sirve para separar el interfaz contractual de una abstracción y su implantación.

**Sistema con encapsulamiento**

![](https://github.com/LuisRoldanC/ProgOO/blob/main/Encapsulamiento.png)

**Sistema sin encapsulamiento**

![](https://github.com/LuisRoldanC/ProgOO/blob/main/Sistema%20sin%20encapsulamiento.jpg)

Suponiendo que es una maquina induastrial el cual tiene cables expuestos y si un trbajador lo mueve sin algun tipo de instructivo o conocimiento puedo ocasionar cierto error en la maquina

La encapsulación permite definir niveles de visibilidad para los elementos de la clase, y evita que las clases se entrelasen entre ellas pudiendo provocar un error al momento de querer utilizar variables, metodos etc, y se solucionaria poniendole un nivel de acceso al objeto que va modificar

__Herencia__

La herencia es el proceso en la cual tienes una clase padre, y esa clase padre al tener hijos, o subclases estas heredan ciertos atributos, como por ejemplo dentro de una familia pueden ser rasgos, o puntos en los cuales son parecidos a su padre o abuelos.

![](https://github.com/LuisRoldanC/ProgOO/blob/main/Herencia.png)


__Referencias bibliograficas__

[https://profile.es/blog/que-son-los-paradigmas-de-programacion/](https://profile.es/blog/que-son-los-paradigmas-de-programacion/)

[https://profile.es/blog/que-es-la-programacion-orientada-a-objetos/](https://profile.es/blog/que-es-la-programacion-orientada-a-objetos/)

[https://www.um.es/docencia/barzana/DIVULGACION/INFORMATICA/Historia-primeros-lenguajes.html#:~:text=1972%20%3A%20Creación%20del%20primer%20lenguaje,Alan%20Kay%20en%20Xerox%20PARC.](https://www.um.es/docencia/barzana/DIVULGACION/INFORMATICA/Historia-primeros-lenguajes.html#:~:text=1972%20%3A%20Creación%20del%20primer%20lenguaje,Alan%20Kay%20en%20Xerox%20PARC.)

[https://styde.net/encapsulamiento-en-la-programacion-orientada-a-objetos/](https://styde.net/encapsulamiento-en-la-programacion-orientada-a-objetos/)

## UML
El Lenguaje de Modelado Unificado (UML, por sus siglas en inglés) es un lenguaje de modelado gráfico que se utiliza para visualizar, especificar, construir y documentar sistemas de software. Fue desarrollado por un grupo de tres autores: Grady Booch, James Rumbaugh e Ivar Jacobson, en la década de 1990.
La primera versión del UML se publicó en 1997, y desde entonces ha evolucionado a través de varias versiones. Actualmente, UML es un estándar de la industria respaldado por el Object Management Group (OMG).

El UML se utiliza en una amplia variedad de sistemas, incluyendo sistemas de software, sistemas de información empresarial, sistemas de telecomunicaciones, sistemas embebidos y sistemas en tiempo real. En años recientes, UML ha seguido siendo ampliamente utilizado en la industria del software y ha sido adoptado por muchas empresas y organizaciones en todo el mundo.

Uno de los diagramas más utilizados en UML es el Diagrama de Clases, que muestra la estructura estática del sistema modelado, incluyendo clases, atributos, métodos y relaciones entre clases. Otros diagramas incluyen el Diagrama de Casos de Uso, que muestra la funcionalidad del sistema, y el Diagrama de Secuencia, que muestra cómo las diferentes partes del sistema interactúan entre sí.

Existen varias herramientas de modelado que admiten UML, como Enterprise Architect, MagicDraw, Rational Rose, Visual Paradigm, entre otras.

En cuanto a empresas que utilizan UML, es común que las empresas de desarrollo de software utilicen esta metodología y lenguaje para modelar sus sistemas. Una de las empresa que lo utiliza es Apple.

## UML de Maquina Expendedora

![](https://github.com/LuisRoldanC/ProgOO/blob/main/Maquina%20UML%202.png)

En el presente diagrama se desarrolla el modelo UML de una Maquina Expendedora, la cual hace referencia a la venta de productos comestibles y de articulos diarios.

Entre las clases que integran la maquina expendedora esta la clase Pago que realiza un conteo con el metodo conteo del el dinero que introduce el usuario a la maquina con la clase efecto y de esta se componen la clase billete y moneda que tiene un atributo de valor de la moneda o billete, acompañados por un getPago, al ingresa el dinero, tenemos una clase maquina expendedora con los metodos de Dispensar el producto, realizar pago y seleccionar producto que estan ligados a una clase almacen que contiene el metodo de getAlmacenamiento que es donde se encuentras los productos y todo el dinero almacenado.

Ahora tenemos una clase producto de la cual tiene los atributos de nombre, precio, cantidad y de esta heredan la clase bebida, que asu vez tiene los atributos de marca y sabor, despues una clase snack que tambien contiene los atributos de tipo y marca, y al final dea clase ArticuloUsoDiario, que tiene atributo de tipo y marca que tienen cardilnalidad que es el total de productos que puede aver en la maquina que en bebidas son de 8 a 1, en snack de 10 a 1 y ArticuloUsoDiario de 5 a 1.

Al igual la clase producto tiene un tipo de producto la cual contiene el nombre del tpo de producto el cual va dispensar la maquina, una vez seleccionado el producto o tecleado el producto que queremos el dispensador con el metodo RealizarPago va cobrar el total del producto seleccionado y el dispensador el cual realizo el pago va activar la clase cambio el cual regresara el dinero sobrante con el metodo de cambio.

__Referencias bibliograficas__

[https://biblus.us.es/bibing/proyectos/abreproy/11005/fichero/apéndice+b.pdf+#:~:text=UML%20es%20una%20notación%20que,et%20al.%2C%201992%5D).](https://biblus.us.es/bibing/proyectos/abreproy/11005/fichero/apéndice+b.pdf+#:~:text=UML%20es%20una%20notación%20que,et%20al.%2C%201992%5D)

