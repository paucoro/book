# Book Paulina

## Inicio :dog:

### HTML

#### - Etiquetas

**HTML** determina el contenido de tu página web.

Estructurar un sitio web con HTML es parecido a un **árbol**, en donde se puede extender el contenido sin importar el nivel de profundidad, en donde un elemento puede tener N número de hijos ( elementos dentro de el ).

Todo nuestro sitio web esta compuesto por **etiquetas HTML**( elementos ), existen etiquetas con cierto valor que ayudan a la estructura de nuestro sitio y que este sea encontrado de una manera mas facil por los buscadores.

La forma en que se estructura una etiqueta HTML es:

```
<NOMBRE_ETIQUETA></NOMBRE_ETIQUETA>
```

:grey_exclamation: Donde podemos observar que una **etiqueta** en casi todos los casos siempre tiene **una apertura y un cierre** representada:

* **< APERTURA >** por medio del nombre de la etiqueta dentro de **<>**.
* **< CIERRE >** por medio del nombre de la etiqueta dentro de **<>**, pero en este caso se agrega un **/** antes del nombre de la **etiqueta**.

#### - Atributos en las etiquetas HTML

Las **etiquetas** pueden contener **N número de Atributos**, los **atributos** son valores adicionales que configuran o modifican el elemento de nuestras etiquetas para cumplir diferentes criterios.

Para poder representar un atributo en una etiqueta HTML se estructura de la siguiente manera.

```
<NOMBRE_ETIQUETA ATRIBUTO="VALOR_DEL_ATRIBUTO"></NOMBRE_ETIQUETA>
```

:grey_exclamation: Donde podemos observar que el atributo **contiene un valor** (aunque no siempre es así) y ademas que el atributo se **agrega en la apertura de nuestra etiqueta**.

Existen muchos atributos especificos para diferentes tipos de etiquetas que tienen diferente funcionamiento, [Aquí hay un enlace donde podrás ver una lista de atributos para las etiquetas ](https://developer.mozilla.org/es/docs/Web/HTML/Atributos), aunque en el transcurso del curso podrás ir viendo los principales atributos que usan diferentes etiquetas.

#### - Elementos hijos dentro de etiquetas HTML

Las **etiquetas** pueden contener valores tanto texto como otras **etiquetas HTML**.

```
<NOMBRE_ETIQUETA>
    <ETIQUETA_HIJO></ETIQUETA_HIJO>
</NOMBRE_ETIQUETA>
```

:grey_exclamation: Este tipo de anidación puede extenderse no importa en nivel de profundidad que se quiera, en donde el padre tiene un nivel de jerarquizacion sobre el hijo,
existen etiquetas que necesitan de otras, depende de la etiqueta y su significado.

#### - Estructura basica de un elemento HTML
