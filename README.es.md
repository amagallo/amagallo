🇬🇧 [English](./README.md)  |  🇪🇸 **Español**

# 👋 Hola, soy Álvaro Magalló Paz

En mi vida profesional, siempre me guía esta pregunta:

> *¿Cómo podemos modelar la mente, con toda su lógica emergente, memoria y restricciones, usando el rigor del hardware, las matemáticas y el diseño de sistemas?*

## 🧠 Qué define mi trabajo

Desde mi adolescencia, he concebido la mente como una estructura modelable **emergente** de la materia, no como algo separado de ella. Durante mis estudios de **Ingeniería Informática**, esta visión evolucionó hacia un gran interés por la intersección entre la Informática y la Psicología, llevándome a centrarme en la **emulación a nivel de hardware y la verificación formal** de arquitecturas cognitivas.

Mi trabajo busca unir el **rigor simbólico** con el **realismo neuronal**, desarrollando sistemas interpretables basados en **trazabilidad**, **métodos formales**, **modelado simbólico** y **diseño inspirado biológicamente**.

## 🔍 Qué construyo

### 🧪 Desarrollo de Hardware Neuromórfico

- **Simulación de circuitos** en VHDL-AMS que representan dinámicas neuronales simplificadas  
- **Traducción simbólica** del comportamiento analógico a restricciones SMT mediante Z3  
- Gráfico de **trazabilidad completa** (Requisitos → Propiedades → Implementación → Verificación)  
- **Cumplimiento** de los estándares DO-254 y DO-333 (ingeniería de sistemas críticos)

### 🧱 Diseño de un Compilador para Tiny

- Diseño completo de una **toolchain de compilación** para **Tiny**, un lenguaje de programación procedural  
- Implementación del **AST en Java 17** usando tipos `record` y despacho por reflexión memorizada  
- Máquina virtual **p-code** personalizada con instrucciones tipadas, pila, gestor de memoria  
- Tipos estructurados (arrays, registros, punteros), paso por valor y por referencia, control de excepciones  
- Memoria basada en un modelo de **RAM en dos niveles** con gestión dinámica tipo FAT

> 📁 [Código fuente en GitHub](https://github.com/amagallo/tiny-compiler)

### 🔢 Hashing Puramente Funcional

- Aplicación de consola interactiva en **Haskell** con una tabla hash basada en primos de Mersenne  
- API personalizada de **enteros grandes** usando listas booleanas y multiplicación de Karatsuba  
- Implementación del **test de Lucas-Lehmer** optimizado para verificación de primos  
- Algoritmos de **resto avanzados** específicos para números tipo Mersenne  
- Uso de **árboles balanceados** como sustitutos de arrays para lograr acceso en tiempo logarítmico

> 📁 [Código fuente en GitHub](https://gist.github.com/amagallo/f15bf0258bc8da12a8103a4e13c6b149)

### 🧠 Análisis del Conectoma Humano

- Análisis de la **conectividad efectiva** usando el algoritmo en reposo de Rolls & Deco  
- Procesado de datos HCP S1200 y parcelación de mapas cerebrales con el atlas HCPex extendido  
- Extracción de redes en estado de reposo y redes activadas por tareas  
- **Visualización axial** de conectomas, alineada con las fluctuaciones dinámicas de conectividad funcional

### ⛏ Programación del Juego de Minería

- Juego de consola en C++ para Windows, renderizado íntegramente en ASCII con colores ANSI  
- Interfaz dinámica con **secuencias de escape** para una estética retro  
- Sistema completo de usuario con autenticación, puntuación y persistencia de sesiones  
- Jugabilidad con recogida de gemas, obstáculos, física con gravedad, dinamita y puntuación estratégica  
- **Tableros de tamaño variable** para fomentar distintas estrategias cognitivas

## 🛠 Stack Tecnológico

- **Métodos Formales**: Z3, SMT, modelado lógico, invariantes, aserciones  
- **Diseño Hardware**: VHDL-AMS, Siemens PartQuest, MBSE, DO-254/DO-333  
- **Lenguajes**: Python, Java, Haskell, Elixir, C++, diseño de DSLs  
- **Matemáticas**: sistemas simbólicos, álgebra, teoría de grafos, teoría de categorías  
- **Modelado**: conectómica, sistemas neuronales artificiales, flujos de verificación

## 🌍 En lo que creo

> *La tecnología debe ser rigurosa, y humana. No solo correcta, sino interpretable. No solo rápida, sino con sentido.*

Creo que construir sistemas no se trata solo de lógica, sino de responsabilidad.  
Crear tecnología que refleje la mente requiere no solo control formal, sino también **cuidado**: por cómo pensamos, cómo vivimos y cómo nos relacionamos.

Veo el trabajo científico como un dilema humano, una forma de crear herramientas al servicio tanto del entendimiento como de la compasión.  
La ingeniería no es solo una disciplina abstracta, sino una forma de **tender puentes entre mentes**, combinando **disciplina de nivel aeroespacial**, **claridad filosófica** y **diseño centrado en las personas**, para construir sistemas que reflejen tanto el **rigor como la empatía**.
