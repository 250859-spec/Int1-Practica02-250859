# Int1-Practica02-250859"
---
En esta practica aprenderemos a utilizar la sherramientas Git y Github para el control de versiones de proyecto de desarrollo de software, aplicando principios de buena practica
en documentos , desarrollo colaborativo y respaldo en la nube del proyecto integrador

Elaborado por: **Paola Franco Gregorio**\

Materia: **Proyecto Integrador**\

Docente: **M.T.Z. Marcco Antonio Ramirez Hernandez**\

Periodo: **Marzo - Agosto 2026*  \

---

## comando basicos para maqutado de la documentacion utilizando el estandar de Markdown (.md)

---

Markdown es el estandar utilizando Git Github para estilizar (maquetar) la documentacion de proyecto entender el contexto y operacion del mismo

### 1. Encabezados o titulos (HEADERS)

Para poder realiza una buena documentacion del proyecto debemos distribuir correctamente los contenidos para poder delimitar o hacer enfasis (enfatizar) es decir resaltar las secciones mas importantes, podemos utilizar lo siguiente:

**EJEMPLO**

# Encabezado de nivel 1
## encabezado de nivel 2
### encabezado de nivel 3
#### encabezado de nivel 4
##### encabezado de nivel 5
###### encabezado de nivel 6
####### encabezado de nivel 7 -  *El estandar solo permite 6 niveles para titulos, a partir del septimo seran presentado como texto plano (sin estilo)*

### 2. separadores (SEPATORS) 

Si se desea marcar una separacion visual de los contenidos podemos utilizar una linea horizontal indicando tres caracteres - continuos, en el maquetado 

**EJEMPLO**

### Titulo de la seccion
---
parrafo 1: este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 

parrafo 2:este texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2, el estandar de markdown distingue los parrafos 

en caso de quue necesitemos alinear el parrafo a **izquierda**, **derecha**, **central** o **justificar** deberemos utilizar una etiqueta <p> con la propiedad align y direccion deseada

<p align="left"> parrafo alineado parrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineado

<p align="center"> parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro 

<p align="right"> parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha 

<p align="justify"> parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafos


### 4. Enfatizado de Texto

- Texto en Negritas: Para resaltar texto importante que no sea un título porque esto inicialmente están en negrita, debremos cerrar el texto desdeado entre dobles asteríscos (**)

Ejemplo: Este texto esta en **negrita**.

- Texto en Cursiva (Itálico): Para hacer referencia a texto utilizando el formato inclinado o itálico bastará con encerrar el texto deseado entre dos asteríscos simples (*).

Ejemplo: Este *texto* estará *inclinado*.

- Texto en Cursiva y Negrita: Para lograr esta estilización en la documentación basta con juntar ambas configuraciones, es decir encerramos el texto en un triple asteríco (***)

Ejemplo: ***Este texto esta en Negrita e Itálico.***

- Texto Tachado: En algunas ocasiones es necesario dar formato al texto con un efecto d ecomo es incorrecto, generalmente esta idea se trasmite porque el texto esta tachado, es decir con un línea que lo marca por la mitad. Para lograr este efecto tendremos que encerrar el texto entre una doble tílde de (~).

Ejemplo: Se dice haya no ~~haiga~~.

- Texto Subrayado: Enj este tipo de formato el texto queda sobre una línea inferior para denotar su relevancia, este formato no tiene una versión rápida en el estándar MARKDOWN, pero dado su similaridad a HTML podemos utilizar las etiquetas ```<u>```y```</u>```.
Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

- Texto en Super Índice: En algunas ocasiones se requiere dar formato a fórmulas estadísticas que requieren potencias entre otras aplicaciones, podemos utilizar el tag de HTML ``` <sup> ```y``` </sup> ``` para delimitar el formato.

Ejemplo: Para elevar x al cuadrado tendríamos lo siguiente x<sup>2</sup>

- Texto en Subíndice: En el caso de Química se utilizan subíndices para representar fórmulas, para ello podemos utilizar el formato de texto con la etiqueta HTML ``` <sub> ```y``` </sub> ```.

Ejemplo: La fórmula del Agua es H<sub>2</sub>O.


### 5. Listas

Cuando realizamos socumentación utilizando el estándar de MARKDOWN, es común que tengamos que listar elementos, requisitos de hardware, requisitos de software o enumerar paso de cómo el software debe ser instalado paso a paso, por eso debemos saber como crear listas de las cuáles hay 3 tipos : **Ordenadas (Números)**, **Desordenadas (Viñetas)** y **Mixtas (Viñetas y Números)**.

1. Listas Ordenadas

Estas deberán estar enumeradas con un número seguido por un punto y un espacio en blanco para comenzar con el listado.
1. PC
2. Wifi
3. Modém
4. Smartphone
5. Smart TV
6. Tablet

Para reiniciar el conteo se debe poner una línea de texto sin numeralia

2. Listas Desordenadas

Estas listas no llevan un número, sino una viñeta (símbolo), y suele listar elementos que no requieren un orden específico.

- Pan
- Leche
- Huevo
- Azúcar

3. Listas Mixtas

Son aquellas que mezclan ambos elementos.

- 3° A DSM
    1. Juan
    2. Pedro
    3. Alejandra
- 3° B DSM
    1. Romina
    2. Daniel
- 3° C DSM
    1. Yahir
    2. Paola
    3. Jeovany
    4. Erick

### 6. Bloques de Código (CODE BLOCKS) o Citas (BLOCK QUOTES)

Estos estilos de texto se utilizan para llamar la atención del lector, en pasos que son importantes, realizar alguna reseña o segmentar líneas de código que se deberán ingresar en una terminal de comandos o líneas de ejecución.

- Cuadros de Citas (Block Quotes)
Son cajas estilizadas en colores grise por defecto con un margen mas claro.

Ejemplo: 

Para listar las carpetas y archivos desde una terminal de comados en el sistema operativo de Windows debemos usar el comando:

> C:/dir

Después oprimimos la tecla *Enter*.

También podemos usar texto multilínea.

EJEMPLO:

Paso para instalar MySQL
> - Descargar el archivo instalador desde la página oficial www.mysql.com
> - Instalar el servidor de Base de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el servicio de Bases de Datos
> - Conectarnos a la base de datos para verificar que se instaló correctamente


- Bloques de código