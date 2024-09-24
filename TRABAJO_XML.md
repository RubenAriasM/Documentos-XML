# Trabajo Tema 1 ADT
## Documentos XML
## Mario Sanchez, Guillermo Muñiz, Rubén Arias

### Descripción del funcionamiento del sistema de almacenamiento
Los sistemas de almacenamiento XML no son bases de datos relacionales tradicionales. En lugar de almacenar datos en tablas con filas y columnas, utilizan documentos XML para representar la información. Estos documentos tienen una estructura jerárquica definida por etiquetas, lo que permite organizar los datos de forma lógica y flexible.

**Ventajas:**
* Flexibilidad
* Legibilidad
* Independencia
* Extensibilidad
* Autodescriptivo

**Desventajas:**
* Verbosidad
* Complejidad
* Falta de estandarización
* Rendimiento

**Usos:**
* Intercambio de datos
* Configuración de aplicaciones
* Almacenamiento de datos heterogéneos
* Generación de informes
* Web service


**XML: Un lenguaje de marcado extensible y su evolución**

**Introducción:** XML, o Extensible Markup Language, es un lenguaje de marcado diseñado para almacenar datos de manera estructurada. Su simplicidad y flexibilidad lo han convertido en una herramienta fundamental en el mundo de la informática.

**Objetivo:** En este trabajo exploraremos el origen, surgimiento, popularización y nivel de adopción de los archivos XML.

## Origen y Surgimiento

* **SGML:** XML tiene sus raíces en el Standard Generalized Markup Language (SGML), un lenguaje de marcado muy poderoso pero complejo.
* **Nacimiento de XML:** El Consorcio World Wide Web (W3C) desarrolló XML con el objetivo de crear un lenguaje más simple y flexible que SGML. La primera versión de XML se publicó en 1998.

## Popularización

* **Factores Clave:**
    * **Simplicidad:** Sintaxis clara y fácil de aprender.
    * **Extensibilidad:** Permite crear lenguajes de marcado personalizados.
    * **Independencia de Plataforma:** Funciona en cualquier sistema operativo.
* **Aplicaciones Iniciales:**
    * **Configuración de Aplicaciones:** XML se utilizó ampliamente para configurar aplicaciones de manera flexible.
    * **Intercambio de Datos:** Protocolos como SOAP adoptaron XML para la comunicación entre sistemas.

## Nivel de Adopción Actual

* **Ámbitos de Aplicación:**
    * **Desarrollo Web:** XML sigue siendo utilizado en la creación de sitios web dinámicos.
    * **Integración de Sistemas:** XML es fundamental en la comunicación entre diferentes sistemas.
    * **Gestión de Contenidos:** Muchos CMS utilizan XML para almacenar y gestionar contenido.
* **Alternativas:**
    * **JSON:** Un formato más ligero y popular en el desarrollo web moderno.
    * **YAML:** Otra alternativa con una sintaxis más concisa.
* **Tendencias Futuras:**
    * A pesar de la competencia, XML sigue siendo relevante debido a su estructura sólida y capacidad de representar datos complejos.


### Casos de uso reales observados (mínimo 3 ejemplos)

1. **Ejemplo: Datos meteorológicos**
    * Servicios web como aquellos que exponen datos meteorológicos suelen utilizar XML para encapsular los datos y permitir que otras aplicaciones los consuman.

<weatherdata>
    <location>
        <city>Madrid</city>
        <country>España</country>
    </location>
    <current_condition>
        <temperature value="25" unit="C"/>
        <humidity value="60" />
    </current_condition>
</weatherdata>

2. **Ejemplo: Estructura de un artículo en un CMS**
    * Muchos sistemas de gestión de contenidos (CMS) utilizan XML para almacenar la estructura y el contenido de un sitio web.


<article>
    <title>Mi primer artículo</title>
    <author>Juan Pérez</author>
    <date>2023-11-20</date>
    <body>
        <paragraph>Este es el contenido del artículo.</paragraph>
        <image src="imagen.jpg" alt="Imagen descriptiva"/>
    </body>
</article>

3. **Ejemplo: Configuración de un editor de texto**
    * Muchos editores de texto y entornos de desarrollo integrados (IDEs) utilizan archivos XML para almacenar preferencias del usuario como tamaño de fuente, esquemas de color y atajos de teclado.


<preferences>
    <font-size>12</font-size>
    <theme>dark</theme>
    <keybindings>
        <save>Ctrl+S</save>
        <undo>Ctrl+Z</undo>
    </keybindings>
</preferences>

## Tipos: Tipos de ficheros, bases de datos representativas

### Tipos de ficheros
1. Ficheros XML sencillos: Documentos estructurados con etiquetas que representan la jerarquía de datos. Pueden ser usados para almacenar información de manera estructurada.
 
2. XML Schema (XSD): Esquemas XML que definen la estructura y restricciones de un documento XML. Se utilizan para validar que un archivo XML siga una estructura y formato específico.
 
3. DTD (Document Type Definition): Similar al XSD, pero con una sintaxis diferente. Se usa para validar la estructura de los documentos XML.
 
4. Ficheros RSS/ATOM: Son tipos de documentos XML utilizados en la sindicación de contenido, por ejemplo, en fuentes de noticias o blogs.
 
 
### Bases de Datos Representativas con XML
 
1. Base de datos XML nativa: Son bases de datos que almacenan directamente documentos XML y permiten consultas usando lenguajes como XPath o XQuery.

2. Bases de datos relacionales con soporte XML: Algunas bases de datos relacionales ofrecen soporte para almacenar y consultar datos XML, aunque no son nativas de XML.


### Casos de Uso Reales de XML
1. Intercambio de Datos en Aplicaciones B2B.
 
2. Servicios Web.
 
3. Sindicadores de contenido: Los archivos RSS (Rich Site Summary) o Atom, que son versiones especializadas de XML, se utilizan para sindicar contenido. Plataformas de noticias, como BBC News, y blogs utilizan RSS en XML para actualizar a sus usuarios sobre contenido nuevo.

