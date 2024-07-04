# **Proyecto:** Invernadero
Este proyecto surgió de la idea de diseñar la clase planta de la cual brotaron nuevas clases y necesitaba una manera de manejar tantas instancias de una forma más efectiva, llegando a tener un mejor control, así como que es divertido y creo que ayudará a la gente a saber más variedades de plantas y sus características.

## Clases:
- **Invernadero:** Clase que es donde se agregan distintos objetos creados desde el main, es la que más metodos tiene de todas precisamente porque se necesita un manejo de tres listas distintas, dentro de sus metodos se incluye uno para agregar nuevos objetos, otro para eliminar, mostrar los objetos ya registrados en la lista y finalmente buscar por coincidencia de atributos.

- **Planta:** Es una clase madre y abstracta lo que impide que se generen instancias de esta y que sirve para declarar atributos en comun que tendrán sus clase hijas así como metodos que se sobreescribiran en estas.

- **Arbol:** Clase hija con atributos propios y que sobreescribe los metodos de la clase madre, para mostrar sus atributos especiales.
  
- **Flor:** Clase hija con atributos propios y que sobreescribe los metodos de la clase madre, para mostrar sus atributos especiales.

- **Arbusto:** Clase hija con atributos propios y que sobreescribe los metodos de la clase madre, para mostrar sus atributos especiales.

## Relaciones entre clases:
- **Agregación:** Se da entre la clase Planta e Invernadero, más especificamente con las hijas de esta, creando 3 listas para agregar objetos de cada una de las clases hijas (las listas actuan como atributos publicos) y poder emplear metodos especificos de estas para varios objetos a la vez.

- **Herencia:** Se da entre la clase Planta (clase madre) y Arbol, Flor y Arbusto (clases hijas), donde Planta hereda sus atributos a estas tres, así como sus metodos, ya sean getters y setters, constructores, etc.

- **Polimorfismo:** Se da con el metodo abstracto declarado como mostrarDatos(), donde cada clase hija lo implementa para imprimir en pantalla sus atributos especiales.

## Futuros Avances:
- **En la clase Invernadero:** Me gustaría reducir un poco la cantidad de lineas de codigo para optimizarlo y tenga una mejor comprensión, quiza alguna de sus partes pueda ir en el main para reducir la carga de lineas en la clase o emplear otras tecnicas como el manejo de enums. Asimismo aprender si hay una mejor forma de usar los metodos de las clases hijas sin la necesidad de crear una lista para cada tipo de objeto

- **En las clases hijas:** Me gustaría implementar otros metodos que no sean solo mostrar atributos, quiza algo para regar los arboles y que con el tiempo den frutos.
- **En la clase madre:** Lo mismo, implementar metodos que no solo impriman datos.
