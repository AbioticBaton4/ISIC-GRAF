# Graficacion (SCC-1010)

Bienvenido al repositorio de la asignatura **Graficacion (SCC-1010)**. En este repositorio encontraras todos los apuntes, practicas y proyectos desarrollados durante el curso, orientados a la generacion de graficos en 2 y 3 dimensiones, su transformacion y efectos diversos.

## Tabla de Contenidos
- [Graficacion (SCC-1010)](#graficacion-scc-1010)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Objetivo de la Asignatura](#objetivo-de-la-asignatura)
  - [Herramientas y Lenguaje de Programacion](#herramientas-y-lenguaje-de-programacion)
  - [Instalacion y Configuracion](#instalacion-y-configuracion)
  - [Temario del Curso (Estructura del Repositorio)](#temario-del-curso-estructura-del-repositorio)
    - [Unidad 1: Introduccion a la graficacion por computadora](#unidad-1-introduccion-a-la-graficacion-por-computadora)
    - [Unidad 2: Graficacion 2D](#unidad-2-graficacion-2d)
    - [Unidad 3: Graficacion 3D](#unidad-3-graficacion-3d)
    - [Unidad 4: Relleno, Iluminacion y Sombreado](#unidad-4-relleno-iluminacion-y-sombreado)
    - [Unidad 5: Introduccion a la Animacion por Computadora](#unidad-5-introduccion-a-la-animacion-por-computadora)
  - [Estructura de Directorios](#estructura-de-directorios)
  - [Licencia](#licencia)

## Objetivo de la Asignatura
Disenar, desarrollar y aplicar modelos computacionales para solucionar problemas de representacion grafica, utilizando las herramientas matematicas necesarias y el lenguaje de programacion **Java** para la creacion de software con interfaces visuales, animaciones y entornos de realidad virtual o simulacion.

## Herramientas y Lenguaje de Programacion
* **Lenguaje:** Java (Uso de librerias nativas como `java.awt`, `javax.swing`, o externas como `JavaFX` / `JOGL` para renderizado avanzado).
* **Control de Versiones:** Git y GitHub.
* **IDE Recomendado:** IntelliJ IDEA, Eclipse o Apache NetBeans.

## Instalacion y Configuracion

Para poder compilar y ejecutar las practicas de este repositorio, es necesario preparar el entorno de desarrollo. Consulta las guias detalladas en la carpeta de configuracion:

1. **Instalacion de Git y GitHub:**
   * Descarga e instala [Git](https://git-scm.com/).
   * Configura tu cuenta y llaves SSH siguiendo la [Guia de Git y GitHub](00_Setup/Guia_Git_GitHub.md).

2. **Entorno de Java:**
   * Descarga e instala el [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) (Se recomienda la version 17 o superior).
   * Configura las variables de entorno (`JAVA_HOME`).
   * Instala tu IDE de preferencia.
   * Mas detalles en la [Guia de Configuracion del Entorno Java](00_Setup/Configuracion_Entorno_Java.md).

## Temario del Curso (Estructura del Repositorio)

El repositorio esta organizado en las 5 unidades que marca el programa educativo (SCC-1010):

### Unidad 1: Introduccion a la graficacion por computadora
Conceptos fundamentales, modelos matematicos, modelos de color y el hardware detras de la graficacion.
* [1.1 Historia y evolucion de la graficacion por computadora](Unidad_1_Introduccion/1.1_Historia_y_evolucion.md)
* [1.2  Áreas de aplicación.](Unidad_1_Introduccion/1.2_Areas_applicacion.md)
* [1.3 Aspectos matemáticos de la graficación.](Unidad_1_Introduccion/1.3_Aspectos_Matematicos.md)
* [1.4 Modelos del color: RBG, CMY, HSV y HSL.](Unidad_1_Introduccion/1.4_Modelos_del_color.md)
* [1.5 Representacion y trazo de lineas y poligonos](Unidad_1_Introduccion/1.5_Representacion_y_trazo.md)
* [1.6 Formatos de imagen.](Unidad_1_Introduccion/1.6_Formatos_de_imagenes.md)
* [1.7 Procesamiento de mapas de bits](Unidad_1_Introduccion/1.6_Procesamiento_mapas_bits.md)

### Unidad 2: Graficacion 2D
Desarrollo y aplicacion de modelos de graficacion y transformacion bidimensional.
* [2.1 Transformacion bidimensional](Unidad_2_Graficacion_2D/2.1_Transformacion_bidimensional.md)
* [2.2 Representacion matricial de las transformaciones bidimensionales](Unidad_2_Graficacion_2D/2.2_Representacion_matricial.md)
* [2.3 Trazo de lineas curvas](Unidad_2_Graficacion_2D/2.3_Trazo_de_lineas_curvas.md)

### Unidad 3: Graficacion 3D
Representacion, visualizacion y transformacion sobre entidades geometricas tridimensionales.
* [3.1 Representacion y visualizacion de objetos en tres dimensiones](Unidad_3_Graficacion_3D/3.1_Representacion_y_visualizacion.md)
* [3.2 Formas geometricas tridimensionales (superficies planas y curvas)](Unidad_3_Graficacion_3D/3.2_Formas_geometricas.md)
* [3.3 Transformaciones tridimensionales](Unidad_3_Graficacion_3D/3.3_Transformaciones_tridimensionales.md)

### Unidad 4: Relleno, Iluminacion y Sombreado
Aplicacion de tecnicas visuales para dar realismo y volumen a los objetos graficos.
* [4.1 Relleno de poligonos](Unidad_4_Relleno_Iluminacion_Sombreado/4.1_Relleno_de_poligonos.md)
* [4.2 Modelos basicos de iluminacion](Unidad_4_Relleno_Iluminacion_Sombreado/4.2_Modelos_basicos_iluminacion.md)
* [4.3 Tecnicas de sombreado](Unidad_4_Relleno_Iluminacion_Sombreado/4.3_Tecnicas_de_sombreado.md)

### Unidad 5: Introduccion a la Animacion por Computadora
Contextos de animacion grafica y realidad virtual considerando aspectos matematicos basicos.
* [5.1 Historia, evolucion y aplicacion de la animacion por computadora](Unidad_5_Animacion_por_Computadora/5.1_Historia_evolucion_aplicacion.md)
* [5.2 Tipos de animacion 2D](Unidad_5_Animacion_por_Computadora/5.2_Tipos_de_animacion_2D.md)
* [5.3 Tipos de animacion 3D](Unidad_5_Animacion_por_Computadora/5.3_Tipos_de_animacion_3D.md)
* [5.4 Animacion 2D o 3D controlada por el usuario](Unidad_5_Animacion_por_Computadora/5.4_Animacion_controlada.md)

## Estructura de Directorios

Cada carpeta de unidad cuenta con sus apuntes teoricos en formato Markdown (`.md`) y un directorio `src/` donde se alojaran los codigos en **Java** correspondientes a las practicas de la unidad. Los manuales de instalacion y configuracion inicial del entorno se encuentran en la carpeta `00_Setup/`.

## Licencia
Este proyecto se distribuye bajo los terminos de la Licencia MIT. Consulta el archivo `LICENSE` para mas detalles.