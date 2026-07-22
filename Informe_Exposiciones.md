# Informe de la exposición del segundo corte sobre las Herramientas CASE

**UNIVERSIDAD TÉCNICA ESTATAL DE QUEVEDO (UTEQ)**
**Facultad de Ciencias de la Computación**
**Carrera de Software**

Informe de las exposiciones y prácticas — Exposición Segundo Corte: Herramientas CASE

- **Estudiante:** Tigasi Sampedro Paul Alexander
- **Curso:** 4to A
- **Materia:** Ingeniería de Requerimientos
- **Docente:** Ing. Gleiston Cicerón Guerrero Ulloa
- **Repositorio GitHub:** https://github.com/ptigasis-Alexander/Exposicion_2Corte_Informe_Tigasi/tree/main
- **Fecha:** 20/07/2026 - 21/07/2026

---

## Grupo A — StarUML

### Díaz

**Diapositiva de presentación**
- **MDD (Desarrollo Dirigido por Modelos):** Es una representación mediante un diagrama.
- **MDE (Model-Driven Engineering):** Lo importante es el diagrama antes del código.
- **MDA (Model-Driven Architecture):** Arquitectura dirigida por modelos. Crea primero el diagrama de clases y luego se le agrega un lenguaje.

**Transformaciones**
- M2M → Modelo → Modelo
- M2T → Texto (código)

**¿Qué es StarUML?**
Herramienta CASE para crear diagramas y soporta extensiones para generar código.

### Escudero

**¿Por qué elegimos StarUML?**
- Compatibilidad y generación de código.
- Permite trabajar con proyectos .NET.
- Además, mantiene la trazabilidad.

**Subsistema modelado**
Presenta los procesos principales del sistema para un gimnasio.
- Registro.

### Mera

**Modelo UML**
Explicación del diagrama de clases, las relaciones entre clases y la cardinalidad.

**Ventajas y limitaciones**

*Ventajas*
- Multiplataforma.
- Ligero.

*Limitaciones*
- Versión gratuita limitada.
- Curva de aprendizaje.
- Menor compatibilidad.

**Comparación de funcionalidades**

*StarUML*
- Enfoque en UML.
- Fácil de aprender.

*Visual Paradigm*
- Ingeniería inversa.
- Reportes completos.

### Práctica
- **Díaz:** Presentación del diagrama, instalación de extensión de C# para la práctica.
- **Mesías:** Guarda el diagrama para generar el código.
- **Mera:** Apertura del código generado e importado en Visual Studio.
- **Escudero:** Realiza cambios en el diagrama para sincronizarlo con el código ya generado.

---

## Grupo G — Umple Online

### Alivia
- Umple Online es una herramienta compatible con varios lenguajes de programación, como C#, Java, C++ y PHP.
- Se realizó una presentación de la herramienta y de sus principales interfaces.

**Práctica**
- Demostración de cómo generar un diagrama a partir del código y cómo generar código a partir de un diagrama (ingeniería inversa y directa).

### Arboleda

**Características**
- Trabaja de forma integrada con el modelo y los diagramas.

### Calle

**Ciclo de desarrollo**
- Permite la concepción y sincronización del modelo.
- Verifica errores y ofrece opciones de simulación.
- Facilita la generación de diagramas a partir del código.

### Práctica
- **Arboleda:** Generación de diagramas a partir del código.
- **Calle:** Generación de diagramas y cambio de lenguaje de programación.
- **Alivia:** Presentación de la interfaz, las funcionalidades y los componentes de la herramienta CASE.

---

> **Versión mejor redactada (para entregar o estudiar)**

## Grupo E — Eclipse Papyrus

### Gamarra Edu

**¿Qué es MDD?**
El Desarrollo Dirigido por Modelos (MDD) es una metodología de desarrollo de software que utiliza los modelos como elemento principal del proceso. Permite transformar modelos UML en código fuente de forma automática.

- **MDE (Model-Driven Engineering):** Enfoque basado en modelos para el desarrollo, la ingeniería de requisitos y la documentación.
- **MDA (Model-Driven Architecture):** Arquitectura dirigida por modelos que separa el modelo de la implementación.
- **MDD:** Facilita la generación automática de código a partir de diagramas UML.

### Pérez

**Niveles de abstracción**
- **CIM (Computation Independent Model):** Describe el negocio y los requisitos sin considerar aspectos técnicos.
- **PIM (Platform Independent Model):** Define la lógica del sistema sin depender de una plataforma específica.
- **PSM (Platform Specific Model):** Adapta el modelo a un lenguaje de programación y a una plataforma o motor de base de datos determinado.

### Gamarra Edu

**Eclipse Papyrus**
- Es una herramienta de modelado UML de software libre.
- Ofrece amplia compatibilidad con el ecosistema Eclipse.
- Permite crear, editar y gestionar modelos UML.

**Acceleo**
Es una herramienta que permite generar código fuente automáticamente a partir de modelos UML mediante plantillas de transformación.

### Pérez

**¿Por qué utilizar Papyrus + Acceleo?**
- Son herramientas de software libre.
- Se integran en un mismo entorno de desarrollo (Eclipse).
- Permiten personalizar la generación de código.
- Facilitan el desarrollo basado en modelos.

**Beneficios del MDD**
- Generación automática de código.
- Mayor productividad.
- Mejor trazabilidad entre modelos y código.
- Mayor calidad del software.
- Disminución de errores durante el desarrollo.

### Práctica
- **Gamarra Edu:** Seleccionó una plantilla en Acceleo para generar código desde un diagrama de clases, guardó el código en una carpeta y modificó el diagrama para ver los cambios reflejados.
- **Pérez:** Corrigió un error en la plantilla de Acceleo y generó correctamente el código del diagrama.

---

## Grupo B — BOUML

### Morales

**Concepto de MDE**
El Model-Driven Engineering (MDE) es una metodología de desarrollo de software que utiliza modelos como elemento principal durante todo el proceso de desarrollo.

**Arquitectura MDA**
- **CIM (Computation Independent Model):** Representa los requisitos y el contexto del negocio.
- **PIM (Platform Independent Model):** Describe el sistema sin depender de una plataforma tecnológica.
- **PSM (Platform Specific Model):** Adapta el modelo a un lenguaje de programación o plataforma específica.

### Jean Pierre

**Historia y funcionamiento de Bouml**
- Bouml utiliza modelos UML para generar código automáticamente.
- Se basa en modelos abstractos durante el desarrollo.
- Soporta diagramas UML estándar.
- Permite trabajar con modelos de requisitos, funcionales y de comportamiento.

### Daniela

**Características de Bouml**
- Es una herramienta de código abierto.
- Presenta una alta velocidad de ejecución.
- Consume pocos recursos del sistema.
- Tiene una interfaz sencilla.
- Puede ampliarse mediante extensiones.
- Es compatible con varios lenguajes de programación, como C#, C++ y Java.

**Comparación de herramientas**

| Herramienta | Característica principal |
|---|---|
| Bouml | Muy simple y ligera. |
| StarUML | Fácil de utilizar y con buena generación de código. |
| Visual Paradigm | Herramienta robusta con más funcionalidades. |

**Ingeniería directa**
Consiste en transformar un modelo UML en código fuente de forma automática, facilitando el desarrollo basado en modelos.

### Herrera

**Ingeniería inversa**
La ingeniería inversa consiste en obtener un modelo UML a partir del código fuente de un sistema ya existente. Esto facilita la comprensión, documentación y mantenimiento del software.

**Ingeniería bidireccional**
La ingeniería bidireccional permite mantener sincronizados el modelo UML y el código fuente. Cualquier modificación realizada en uno de ellos puede reflejarse automáticamente en el otro, garantizando la consistencia entre ambos.

### Práctica
- **Marcillo:** Presentó la herramienta BOUML y sus principales componentes.
- **Herrera:** Demostró la generación automática de código a partir de un diagrama UML.

---

## Grupo D — Modelio

### Rizo
Modelio es una herramienta libre para crear diagramas UML y BPMN. Genera una amplia variedad de modelos orientados al análisis de sistemas.

Fue adquirido por la empresa Objecteering en 2011, lo que fortaleció su uso en universidades y proyectos académicos.

**Características**
- UML Models.
- Soporte multiplataforma.
- Organización de proyectos.

### Crespo
Tiene una interfaz sencilla.

Permite crear diagramas UML como:
- Diagrama de estructura.
- Diagrama de comportamiento.
- Diagrama BPMN.
- Análisis de requisitos.

**Extensiones y modelos**
Permite personalizar clases y atributos.

Cuenta con módulos de Java para la generación automática de código.

### Amagua

**Ventajas**
- Gratuito.
- Soporta UML, BPMN y ArchiMate.
- Agregación de modelos.
- Arquitectura modular extensible.

**Desventajas**
- Curva de aprendizaje.
- Funciones avanzadas.
- No procesa código de forma manual.

**Comparación**
- Modelio
- StarUML
- Visual Paradigm
- Enterprise Architect

**Trabajo**
- Tabla de documentación y reutilización.

**Conclusión**
Facilita el trabajo y el desarrollo de proyectos.

### Práctica
- **Rizo:** Presentación de la herramienta, sus funciones y componentes, y organización de la jerarquía de carpetas.
- **Crespo:** Configuración de la generación de código y personalización del código a generar, incluyendo los atributos, las relaciones y las cardinalidades.
- **Amagua:** Creación de un diagrama a partir de un requisito de actividad (Activity Diagram).

---

## Grupo C — Visual Paradigm

### Castro

**Fundamentos de software**
- MDE → MDA → CIM, PIM y PSM → MDS.

### Villafuerte

**¿Por qué se usó?**
Por qué se usaron los archivos .vpn anteriormente.

### Castro

**Estereotipos y perfiles UML**
- Entity
- Service
- Repository

### Mera

**Configuración de generación**
- Uso del lenguaje Java.
- Asociación múltiple.
- Carpeta de salida.
- Configurar y utilizar la vista previa para generar el código sin errores.

### Vera

**Convenciones y estructura**
- Se genera de manera automática.
- Validaciones.
- Reglas de negocio.
- Manejo de errores.

### Práctica
- **Villafuerte:** Presentación de la herramienta, el diagrama y sus relaciones.
- **Castro:** Presentación de estereotipos y validación de diagramas y sus clases.
- **Mora:** Configuración para la generación de código a partir del diagrama.
- **Vera:** Generación de código en lenguaje C#, aplicando la modificación del diagrama al código ya generado.

---

## Grupo F

### Alcívar
Introducción de los modelos UML.

### Barrionuevo
- Funcionalidades: explicación de la generación de código y validación de los modelos antes de ejecutar el código.
- Interfaces intuitivas y ligeras.
- Análisis comparativo: es una herramienta basada en archivos.

### Quintero

**Ventajas**
- Aceleración en el proceso de desarrollo.
- Trazabilidad desde los requisitos hasta la aplicación del requisito.
- Creación de diagramas siguiendo los estándares UML.

**Limitaciones**
- Curva de aprendizaje alta.
- ¿Por qué se eligió esta herramienta?
- Por ser una herramienta CASE.

### Práctica
- **Alcívar:** Creación de diagrama de requerimientos.
- **Barrionuevo:** Creación de diagrama de caso de uso.
- **Quintero:** Creación del diagrama de clases, generación de código y aplicación de la ingeniería inversa.
