# 2. Procesos de Gestión de Proyecto

Contenidos:

- [2. Procesos de Gestión de Proyecto](#2-procesos-de-gestión-de-proyecto)
  - [2.1. Ámbito del Software](#21-ámbito-del-software)
    - [Preguntas para realizar el levantamiento inicial de requerimientos de un sistema.](#preguntas-para-realizar-el-levantamiento-inicial-de-requerimientos-de-un-sistema)
    - [TFEA](#tfea)
  - [Estudio de Factibilidad](#estudio-de-factibilidad)
  - [2.3. Análisis de Riesgos](#23-análisis-de-riesgos)
    - [Matriz de probabilidad](#matriz-de-probabilidad)
    - [Matriz de consecuencia](#matriz-de-consecuencia)
    - [Matriz de valoración de riesgos](#matriz-de-valoración-de-riesgos)
  - [2.5. Mediciones](#25-mediciones)
    - [2.5.1. Métricas](#251-métricas)
    - [2.5.2 Modelos de estimación](#252-modelos-de-estimación)
      - [Ejercicio 1](#ejercicio-1)
      - [Ejercicio 2](#ejercicio-2)
      - [COCOMO](#cocomo)
        - [Submodelos](#submodelos)
        - [Esquema de modos de desarrollo de software.](#esquema-de-modos-de-desarrollo-de-software)
        - [Ecuaciones por tipo de modelo COCOMO: Básico e Intermedio](#ecuaciones-por-tipo-de-modelo-cocomo-básico-e-intermedio)
        - [Valores constantes por modo de desarrollo](#valores-constantes-por-modo-de-desarrollo)
      - [COCOMO II](#cocomo-ii)
        - [PMAT Ratings for Estimated Process Maturity Level (EPML)](#pmat-ratings-for-estimated-process-maturity-level-epml)
        - [Valores de Factores de Escala](#valores-de-factores-de-escala)
        - [Constantes de calibración del modelo](#constantes-de-calibración-del-modelo)
        - [Fórmulas Generales](#fórmulas-generales)
          - [Fórmula de esfuerzo:](#fórmula-de-esfuerzo)
          - [Fórmula de tiempo calendario](#fórmula-de-tiempo-calendario)
      - [COCOMO II: Multiplicadores de Esfuerzo](#cocomo-ii-multiplicadores-de-esfuerzo)
  - [Glosario de Términos](#glosario-de-términos)

## 2.1. Ámbito del Software

- **Ámbito**: conjunto de funcionalidades y razgos que se va a ejecutar dentro de
  un contexto definido.
  - Contexto.
  - Objetivos de información.
  - Función y desempeño.
- **Recolección de Información**
  - Preguntas de contexto libre
  - Meta-cuestiones

### Preguntas para realizar el levantamiento inicial de requerimientos de un sistema.

A continuación se dará una lista de preguntas que podremos utilizar para
obtener la información más básica de un sistema o en una reunión con algún
cliente.

- ¿Por qué medio se enteró de nosotros?
- ¿En qué le podemos ayudar?
- ¿Por qué nos contactó?
- ¿Existe algún sistema? ¿Lo podemos revisar?
- ¿Podemos contactar a las personas que lo hicieron?
- ¿Cuál es el problema?
- ¿Quiénes van a usar el sistema?
- ¿Quiénes van a ser los beneficiados?
- ¿Cuáles son sus procesos?
- ¿Cuánto tiempo tardan?
- ¿Tienen manuales?
- ¿Manejan algún formato?
- ¿Qué datos contiene?
- ¿Qué se hace para registrar un pedido?
- ¿Cuáles son las alternativas?
- ¿Qué materiales necesita para elaborar el producto?
- ¿Quiénes son sus proveedores?
- ¿Qué se hace cuando el cliente pide una factura o exige una devolución?
- ¿El personal cuenta con conocimientos?
- ¿Cuáles serían las restricciones?
- ¿Cuáles son las reglas del negocio?
- ¿Es importante la seguridad de los datos? ¿A qué nivel?
- ¿En dónde se instalará el sistema?

### TFEA

TFEA (Facilitated Application Specification Techniques) es _Técnicas para
facilitar las especificaciones de la aplicación_.

- Punto de reunión.
- Normas.
- Agenda flexible.
- Moderador.
- Material para trabajar.

## Estudio de Factibilidad

¿Qué es la factibilidad?

- Evaluación técnica.
- Evaluación operativa.
- Evaluación ambiental.
- Evaluación económica.
- Evaluación social.

Modelo de estudio de factibilidad

- Resumen ejecutivo.
- Antecedentes del proyecto.
- Descripción del proyecto y su contexto.
- Alcance del estudio de factibilidad.

## 2.3. Análisis de Riesgos

- ¿Qué es un riesgo?
  - Pequeños o grandes problemas que pueden o no suceder.
- Riesgo de software (tiempo, costo, calidad, rendimiento)
  - Tecnología
  - Requerimientos
  - Personal
  - Técnicos
  - Empresariales
- Componentes y promotores de Riesgo
  - Rendimiento
  - Costo
  - Apoyo (mantenibilidad)
  - Calendario
- Gestión de Riesgos
  - Identificación de riesgos
  - Análisis de riesgos
    - Definir probabilidad
    - Definir consecuencia o impacto
    - Priorizar
- Manejo de Riesgos
  - Estrategias de prevención (posibilidad)
  - Estrategias de minimización (impacto)
  - Planes de contingencia
- Supervisión de riesgos

### Matriz de probabilidad

| ¿Qué tan frecuente? | Valor | Valor en % |
| :-----------------: | :---: | :--------: |
|      Frecuente      |   5   | 75% - 100% |
|      Probable       |   4   |  50%- 75%  |
|      Ocasional      |   3   | 25% - 50%  |
|       Posible       |   2   | 10% - 25%  |
|      Imposible      |   1   | Menor a 1% |

### Matriz de consecuencia

| ¿Cuál sería la consecuencia? | Valor |
| :--------------------------: | :---: |
|         Catastrófico         |   E   |
|          Peligroso           |   D   |
|           Moderado           |   C   |
|            Menor             |   B   |
|        Insignificante        |   A   |

### Matriz de valoración de riesgos

![Matriz de valoración de riesgos][imagen-matriz-valoracion-riesgos]

## 2.5. Mediciones

Para poder estimar y medir cómo va nuestro producto de software tenemos que contar con distintos mecanismos y técnicas para poder medir y estimar los costos y tiempos de nuestro proyecto.

### 2.5.1. Métricas

Una métrica es una medida estándar de un grado en el que un sistema de software
o un proceso de software posee en sus propiedades. Estas métricas nos van a
ayudar a realizar nuestras estimaciones. Para esto le vamos a colocar un valor
cuantitativo a un aspecto cualitativo del producto de software.

- Métrica
  - Datos cualitativos
  - Toma en cuenta:
    - Funcionalidad
    - Complejidad
    - Eficiencia
  - Da un valor al atributo de un producto.
- Características de las métricas de software:

  - Simple y calculable.
  - Congruente y objetiva.
  - Efectivo en la retroalimentación a la calidad.

- Alan J. Al-bricht, 1979: necesita tomar en cuenta la funcionalidad del sistema, sino, para él no es una buena estimación.

### 2.5.2 Modelos de estimación

- Análisis de puntos de función (function point analysis).
- International Function Point User Group, 1986 (IFPUG).
- Especificaciones funcionales (interacción y almacenamiento).
  - Valores de dominio de información:
    - **Número de entradas externas (EE)**: entradas que produce el usuario, puede producir un cambio en nuestra tabla de datos, modifica la base de datos. El lector de código de barras, el código QR, la contraseña, un formulario etc. Puede ser una _alta_, una _baja_ o un _cambio_.
    - **Número de salidas externas (SE)**: van a expresar los resultados del sistema, y se lo mostramos al usuario, listas, reportes, también pueden ser mensajes de error, la parte intuitiva de un sistema, cuando transferimos datos a una USB externa o a otro sistema.
    - **Número de consultas externas (CE)**: flujo bidireccional de datos, no generan ninguna modificación en la tabla de datos.
    - **Número de archivos lógicos internos (ALI)**: son las tablas de datos.
    - **Número de archivos de interfaz externos (AIE)**: son las peticiones que se hacen a otros sistemas.

Clasificaciones de cada uno de los _valores de dominio de información_:

![Imagen de Modelos de Estimación][imagen-modelos-estimacion]

Valores de dominio de información:

![Valores de dominio de información][imagen-valores-dominio-información]

Necesitamos saber cuál es el **valor de ajuste**, para esto tenemos los siguientes _factores de complejidad_:

![Factores de Complejidad][imagen-factores-complejidad]

Consideraciones para nuestras estimaciones:

- Salario del desarrollador de software
- Puntos de función sin ajustar (PFSA)
- PUntos de función ajustados (PFA)
- Factor de ajuste (FA)
- Horas efectivas (6)
- Hora de PF promedio (8)
- Número de desarrolladores
- Días laborables al mes (20)
- Otros gastos.

> Para esta materia sólamente usaremos **dos decimales siempre**

Fórmulas:

- $\text{PFA} = \text{PFSA} \times (0.65 + (0.01 \times FA))$
- $\text{horas} = \text{PFSA} \times \text{horas PF promedio}(8)$
- $\text{Días} = \text{horas} / \text{horas efectivas por día}(6)$
- $\text{Meses} = \text{Días}/20$
- $\text{Costo} = \text{Número de desarrolladores} \times \text{meses} \times \text{salario} + \text{otros gastos}$

> Otros gastos: viáticos, renta de lugar, renta de servidores, internet, hardware, licencias, capacitación, luz, gas, agua, papelería, etc.

#### Ejercicio 1

En clase resolvimos el siguiente ejercicio:

![Imagen del Ejercicio de Estimación visto en clase][imagen-ejercicio-estimacion]

> Se le conoce también como _Diagrama de Contexto_.

- Número de entradas externas (EE): 3, contraseña, botón de pánico, activar desactivar
- Número de salidas externas (SE): 2, mensajes y estado de sensor.
- Número de consultas externas (CE): 2, consulta de zona y consulta de sensor.
- Número de archivos lógicos internos (ALI): 1, subsistema monitoreo y respuesta (son tablas).
- Número de archivos de interfaz externos (AIE): 4, sensor de prueba, establecimiento de zona, activar/desactivar y alerta de alarma.

#### Ejercicio 2

Lo primero que debemos hacer es llenar la siguiente tabla:

![Tabla inicial ejercicio 2][imagen-ejercicio-2-estimacion]

- Aquí tomamos todos como simples porque realmente son muy simples (contraseña y demás).
- Seguimos el orden de evaluación:
  1. PFA: aquí se vale hacer el redondeo.
  2. Horas
  3. Días
  4. Meses
  5. Costo
- Realizamos las operaciones _paso a paso_, ojo: el profesor pidió que no nos saltáramos pasos en los cálculos porque necesita ver de dónde salieron los valores intermedios.

#### COCOMO

_Constructive Cost Model (COCOMO)_ es un modelo matemático para la estimación de costos.

##### Submodelos

- Básico: cuando solo nos dan KLDC (_Kilo Líneas de Código_, _Miles de Líneas de Código_).
- Intermedio: cuando nos dan atributos de hardware, personal, personal, proyecto y producto.
- Avanzado: impacto de los conductores de coste.

Aquí elegiremos en función de qué cosas se nos dan en el problema.

##### Esquema de modos de desarrollo de software.

A partir del submodelo seleccionado, usaremos un modo de desarrollo a partir del tamaño y requisitos:

| Modo de Desarrollo |  Requisitos  |          Tamaño           | Complejidad | Personas | Experiencia |
| :----------------: | :----------: | :-----------------------: | :---------: | :------: | :---------: |
|     Orgánicao      | Poco rígidos | Pequeño (menor a 50k LDC) |   Pequeña   |  Pocas   |    Mucha    |
|    Semiacoplado    |  Poco/medio  |  Medio (50k a 300k LDC)   |    Medio    |  Medio   |    Medio    |
|     Emportrado     |     Alto     | Grande (mayor a 300k LDC) |    Alta     |   Alta   |    Poca     |

##### Ecuaciones por tipo de modelo COCOMO: Básico e Intermedio

- $ME$: para calcular esto, se debe consultar la tabla de _Multiplicadores de Esfuerzo (ME)_, obtener los valores y multiplicarlos entre sí.
  - Por ejemplo, si nos dijeran que solo hay que considerar Reliabilidad (RELY) y Experiencia de Aplicación (A), por lo que realizamos la multiplicación de los valores.

|    Ecuación    |        Submodelo Básico        |           Submodelo Intermedio           |
| :------------: | :----------------------------: | :--------------------------------------: |
| Esfuerzo ($E$) | $(E)=a \times (\text{KLDC})^b$ | $(E)=a \times (\text{KLDC})^b \times ME$ |
|  Tiempo ($T$)  |      $(T)=c \times (E)^d$      |           $(T)=c \times (E)^d$           |
| Personal ($P$) |           $(P)=E/T$            |                $(P)=E/T$                 |

##### Valores constantes por modo de desarrollo

| Modo de Desarrollo | COCOMO básico $a$ | COCOMO intermedio $A$ |  $b$  |  $c$  |  $d$  |
| :----------------: | :---------------: | :-------------------: | :---: | :---: | :---: |
|      Orgánico      |        2.4        |          3.2          | 1.05  | 2.50  | 0.38  |
|    Semiacoplado    |        3.0        |          3.0          | 1.12  | 2.50  | 0.35  |
|     Empotrado      |        3.6        |          2.8          | 1.20  | 2.50  | 0.32  |

#### COCOMO II

Factores de escala:

- **Precedencia (PREC)**: la experiencia que tienes en el sistema que estás haciendo en este momento.
- **Flexibilidad de Desarrollo (FLEX)**: la flexibilidad del cliente ante el desarrollo que se va a hacer.
- **Resolución de arquitectura / Riesgo (RESL)**: qué tan bien estamos haciendo los modelos y arquitectura de software y qué tan bien estamos haciendo análisis de riesgos.
- **Cohesión de Equipo (TEAM)**: habla sobre los stakeholders.
- **Madurez del proceso (PMAT)**: habla sobre el equipo de desarrollo y nos dice qué tan bien estan nuestros procesos para poder producir productos de software.

La sumatoria de los factores de cada uno van a resultar en el factor de escala.

##### PMAT Ratings for Estimated Process Maturity Level (EPML)

| PMAT Rating |      Maturity Level      | EPML  |
| :---------: | :----------------------: | :---: |
|  Very Low   | CMM Level 1 (lower half) |   0   |
|     Low     | CMM Level 1 (upper half) |   1   |
|   Nominal   |       CMM Level 2        |   2   |
|    High     |       CMM Level 3        |   3   |
|  Very High  |       CMM Level 4        |   4   |
| Extra High  |       CMM Level 5        |   5   |

##### Valores de Factores de Escala

| Driver | Very Low |  Low  | Nominal | High  | Very High | Extra High |
| :----: | :------: | :---: | :-----: | :---: | :-------: | :--------: |
|  PREC  |   6.20   | 4.96  |  3.72   | 2.48  |   1.24    |    0.00    |
|  FLEX  |   5.07   | 4.05  |  3.04   | 2.03  |   1.01    |    0.00    |
|  RESL  |   7.07   | 5.65  |  4.24   | 2.83  |   1.41    |    0.00    |
|  TEAM  |   5.48   | 4.38  |  3.29   | 2.19  |   1.10    |    0.00    |
|  PMAT  |   7.80   | 6.24  |  4.68   | 3.12  |   1.56    |    0.00    |

##### Constantes de calibración del modelo

- $A = 2.94$
- $B = 0.91$
- $C = 3.67$
- $D = 0.28$

##### Fórmulas Generales

- $PM$: esfuerzo en persona mes (152 horas).
- $\text{Size}$: tamaño en miles de LOCs (KLOCs) o puntos de función **no ajustados**.
- $EM$: multiplicadores de esfuerzo.
- $SF$: factores de escala exponencial.
- $E$: incremento de esfuerzo para proyectos grandes.

###### Fórmula de esfuerzo:

$$PM_{NS} = A \times \text{Size}^E \times \prod_{i = 1}^n EM_i$$

dónde:

$$E = B + 0.01 \times \sum_{j=1}^5 SF_j$$

###### Fórmula de tiempo calendario

$$TDEV_{NS} = C \times (PM_{NS})^F$$

dónde:

$$F = D + 0.2 \times 0.01 \times \sum_{j=1}^5 SF_j$$

#### COCOMO II: Multiplicadores de Esfuerzo

- RCPX: 
  - Qué tan complejo es el sistema que vamos a hacerle al cliente.
  - Que los errores no sean catastróficos
  - El número y tamaño de base de datos estamos usando
  - Qué tan compleja o completa quiere la documentación.
- RUSE:
  - Qué tan fácil es mejorar o modificar el sistema.
- PDIF:
  - Dificultad de plataforma
  - Capacidad de respuesta
  - Capacidad de ejecución
  - Todo lo que tenga que ver con el rendimiento de una computadora en el sistema.
- PERS:
  - Personal capability
  - Conocimientos y habilidades del equipo de desarrollo
- PREX:
  - Cuánto tiempo llevan desarrollando productos de software.
- FCIL:
  - Facilities available
  - Es que instalaciones están disponibles
- SCED:
  - Presión de la agenda
  - Qué tanto le urge al cliente


## Glosario de Términos

Tabla de Datos
: Archivos lógicos internos.

KLDC
: _Kilo Líneas de Código_.
: Miles de líneas de código.

Stakeholders
: Son las partes interesadas en un proyecto.

[imagen-matriz-valoracion-riesgos]: img/matriz-riesgos.png
[imagen-modelos-estimacion]: img/2-5-2-modelos-estimacion.png
[imagen-valores-dominio-información]: img/valores-dominio-informacion.png
[imagen-factores-complejidad]: img/factores-complejidad.png
[imagen-ejercicio-estimacion]: img/ejercicio-estimacion.png
[imagen-ejercicio-2-estimacion]: img/ejercicio-2-estimacion.png
