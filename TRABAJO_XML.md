# Trabajo Tema 1 ADT

## Documentos XML
**XML: Un lenguaje de marcado extensible y su evolución**

**Introducción:** XML, o Extensible Markup Language, es un lenguaje de marcado diseñado para almacenar datos de manera estructurada. Su simplicidad y flexibilidad lo han convertido en una herramienta fundamental en el mundo de la informática.

**Objetivo:** En este trabajo exploraremos el origen, surgimiento, popularización y nivel de adopción de los archivos XML.

## Origen y Surgimiento

* **SGML:** XML tiene sus raíces en el Standard Generalized Markup Language (SGML), un lenguaje de marcado muy poderoso pero complejo.
* **Nacimiento de XML:** El Consorcio World Wide Web (W3C) desarrolló XML con el objetivo de crear un lenguaje más simple y flexible que SGML. La primera versión de XML se publicó en [1998].

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