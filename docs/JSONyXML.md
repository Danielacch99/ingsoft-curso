#  ¿Qué es JSON y XML?
<br>

Definamos primero qué es JSON. Segun la propia página de JSON: 

JSON (acrónimo de JavaScript Object Notation, 'notación de objeto de JavaScript') es un formato de texto sencillo para el intercambio de datos. Se trata de un subconjunto de la notación literal de objetos de JavaScript.  JSON es de fácil lectura y escritura para los usuarios. JSON es fácil de analizar y generar por parte de las máquinas. Es un formato de texto que es completamente independiente del lenguaje pero utiliza convenciones que son ampliamente conocidos por los programadores de la familia de lenguajes C, incluyendo C, C++, C#, Java, JavaScript, Perl, Python, y muchos otros. Estas propiedades hacen que JSON sea un lenguaje ideal para el intercambio de datos.

Ahora veamos qué es XML:

XML es un lenguaje de marcado similar a HTML. Significa Extensible Markup Language (Lenguaje de Marcado Extensible) y es una especificación de W3C como lenguaje de marcado de propósito general. Esto significa que, a diferencia de otros lenguajes de marcado, XML no está predefinido, por lo que debes definir tus propias etiquetas. El propósito principal del lenguaje es compartir datos a través de diferentes sistemas, como Internet.

XML no ha nacido únicamente para su aplicación en Internet, sino que se propone como un estándar para el intercambio de información estructurada entre diferentes plataformas. Se puede usar en bases de datos, editores de texto, hojas de cálculo y casi cualquier cosa imaginable.

XML es una tecnología sencilla que tiene a su alrededor otras que la complementan y la hacen mucho más grande, con unas posibilidades mucho mayores. Tiene un papel muy importante en la actualidad ya que permite la compatibilidad entre sistemas para compartir la información de una manera segura, fiable y fácil.

**Características de JSON:**

* JSON es solo un formato de datos
* Requiere usar comillas dobles para las cadenas y los nombres de propiedades. Las comillas simples no son válidas.
* Una coma o dos puntos mal ubicados pueden producir que un archivo JSON no funcione. 
* Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos. Así, por ejemplo, una cadena o un número único podrían ser objetos JSON válidos.
*  A diferencia del código JavaScript, en el que las propiedades del objeto pueden no estar entre comillas, en JSON solo las cadenas entre comillas pueden ser utilizadas como propiedades.

**Características de XML:**

* Asegura un excelente desempeño, simplicidad de implementación y sencillez de uso en servicios de la web.
* Posibilita que el contenido de los documentos XML sea entendible tanto para las personas como para los dispositivos.
* Permite incluir metadatos en el mismo documento.
* Permite exportar los datos contenidos a otros formatos como por ejemplo HTML, PDF, RTF.
* El estándar XML usa reglas de generación de datos concretas.
* XML es un estándar abierto.
* XML no requiere licencia.

**Usos de Json:**

* Se utiliza principalmente para transferir datos entre un servidor y un cliente.
* Los desarrolladores usan JSON para trabajar con AJAX (JavaScript asíncrono y XML, por sus siglas en inglés).
* Se utiliza hoy en día para compartir información entre diferentes aplicaciones y lenguajes.
* JSON puede ser leído por cualquier lenguaje de programación. Por lo tanto, puede ser usado para el intercambio de información entre distintas tecnologías.

**Usos de XML:**

* Intercambio de datos entre sistemas,
* Base de datos
* Migración de datos
* Aplicaciones web
* Descripción de metacontenidos.

**Ventajas de JSON:**

* Es autodescriptivo y fácil de entender.
* Su sencillez le ha permitido posicionarse como alternativa a XML.
* Es más rápido en cualquier navegador.
* Es más fácil de leer que XML.
* Es más ligero (bytes) en las transmisiones.
* Se parsea más rápido.
* Velocidad de procesamiento alta.
* Puede ser entendido de forma nativa por los analizadores de JavaScript.

**Desventajas de JSON:**

* Algunos desarrolladores encuentran su escueta notación algo confusa.
* No cuenta con una característica que posee XML: extensibilidad.
* No soporta grandes cargas, solo datos comunes.
* Para la seguridad requiere de mecanismos externos como expresiones regulares.

**Ventajas de XML:**

* Tiene un formato estructurado y fácil de comprender.
* Separa radicalmente la información o el contenido de su presentación o formato.
* Está diseñado para ser utilizado en cualquier lenguaje o alfabeto.
* Su análisis sintáctico es fácil debido a las estrictas reglas que rigen la composición de un documento.
* Tiene soporte a cualquier tipo de datos.
* Se pueden definir estructuras complejas y reutilizables.

**De
sventajas de XML:**

* El formato es sumamente estricto.
* Lleva más tiempo procesarlo.
* Complejidad de analizador (parser).
* Un error en cualquier parte del formato puede hacer que todo el documento sea inválido.

#### Tabla comparativa entre JSON y XML.
<br>

|**Características**|**XML**|**JSON**|
|---------|--------|----------|
|Simplicidad|Compatible|compatible|
|Datos autodescritos|Disponible|Disponible|
|Extensibilidad|Disponible|Disponible|
|Legibilidad|Legible para programadores|Legible para todos los usuarios|
|Integración|Disponible|Disponible|
|Compartir datos tradicionales|Complejo|Simple|
|Compartir documentos|Disponible|No disponible|

<br>

#### Ejemplos de JSON y XML:
<br>

##### Persona: 
<br>

JSON:

````JSON

{
    "persona":{
       "nombre":"Daniela",
       "edad":22,
       "estudios":["Primaria","Secundaria", "Preparatoria", "Licenciatura", "Maestría", "Doctorado"]
    }
}

````

XML:

````XML

<persona>
    <nombre>Daniela</nombre>
    <edad>22</edad>
    <estudios>
        <estudio>Primaria</estudio>
        <estudio>Secundaria</estudio>
        <estudio>Preparatoria</estudio>
        <estudio>Licenciatura</estudio>
        <estudio>Maestría</estudio>
        <estudio>Doctorado</estudio>
    </estudios>
</persona>

````

##### Cliente:
<br>

JSON:

```JSON

{
  "Clientes": {
    "Cliente": {
      "id": "123",
      "Nombre": "Gervacio Pérez López",
      "Direccion": {
        "verificada": "si",
        "Calle": "Río San Joaquín",
        "Numero": "432",
        "Ciudad": "Ciudad de México",
        "CodigoPostal": "89586",
        "Pais": "México"
      }
    }
  }
}

```

XML:

```xml

<Clientes>
  <Cliente id="123">
  	<Nombre>Gervacio Pérez López</Nombre>
	<Direccion verificada="si">
            <Calle>Río San Joaquín</Calle>
            <Numero>432</Numero>
	    <Ciudad>Ciudad De México</Ciudad>
	    <CodigoPostal>89586</CodigoPostal>
            <Pais>México</Pais>
         </Direccion>
  </Cliente>
</Clientes>

```

#### Libro:
<br>

JSON:

````JSON

{
  "libros": {
    "libro": {
      "nombre": "La Divina Comedia",
      "year": "1321",
      "id": "45",
      "autores": {
        "nombre": [
          "Dante Alighieri"
        ]
      }
    }
  }
}

````

XML:

````XML

<libros>
  <libro id="45" year="1321">
    <nombre>La Divina Comedia</nombre>
    <autores>
        <nombre>Dante Alighieri</nombre>
    </autores>
  </libro>
</libros>

````


### Referencias:
<br>

* JSON. (s. f.). JSON. Recuperado 12 de octubre de 2021, de https://www.json.org/json-es.html

* Introducción a XML - XML: Extensible Markup Language | MDN. (2021, 12 octubre). MDN Web Wocs. https://developer.mozilla.org/es/docs/Web/XML/XML_introduction

* Barrera, A. (2019, 10 noviembre). JSON: ¿Qué es y para qué sirve? NextU LATAM. https://www.nextu.com/blog/que-es-json/#:%7E:text=Caracter%C3%ADsticas%20de%20JSON%3A,un%20archivo%20JSON%20no%20funcione.

* Marker, G. (2019, 24 noviembre). ¿Qué es XML? ¿Para qué sirve? Características y ventajas. Tecnología Fácil. https://tecnologia-facil.com/que-es/que-es-xml-para-que-sirve-caracteristicas-y-ventajas/#Caracteristicas_deXML

* A., D. (2021, 27 julio). ¿Qué es JSON? Tutoriales Hostinger. https://www.hostinger.mx/tutoriales/que-es-json

* de la Cruz, H. (2017, 19 septiembre). XML, la solución ante la diversidad de formatos. Iberdok. https://iberdok.com/2017/06/22/xml-la-solucion-ante-la-diversidad-de-formatos/

* Comparación de las ventajas y desventajas de JSON y XML - programador clic. (s. f.). Programador clic. Recuperado 12 de octubre de 2021, de https://programmerclick.com/article/62861623501/

* ÁLvarez, G. (2019, 27 abril). Formatos de intercambio de datos XML o JSON. Kyocode. https://www.kyocode.com/2018/10/formatos-intercambio-datos-xml-json/

* F. (2012, 19 abril). Ventajas y Desventajas de XML. fundamentosdexml. https://fundamentosdexml.wordpress.com/2012/04/19/ventajas-y-desventajas-de-xml-2/
