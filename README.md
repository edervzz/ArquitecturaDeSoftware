# Arquitectura de Software 🏗️

## 1. ¿Qué es la arquitectura de software? 🎓

La arquitectura de software se puede entender desde tres perspectivas fundamentales:

### Visión de alto nivel
Es el "esqueleto" o blueprint de un sistema. Define:
- Los componentes principales
- Sus relaciones e interfaces
- Los entornos de ejecución
- Cómo estos elementos se integran para satisfacer tanto requisitos funcionales como no funcionales (rendimiento, disponibilidad, seguridad)

### Gestión de la complejidad
Proporciona una abstracción para organizar sistemas de gran escala, equilibrando factores críticos como:
- Tiempos de respuesta
- Tolerancia a fallos
- Escalabilidad
- Costos operativos

### Decisiones estratégicas
Determina aspectos cruciales como:
- Selección de tecnologías
- Estrategias de escalamiento
- Patrones arquitectónicos a evitar
- Decisiones tempranas de alto impacto

## 2. ¿Qué es el diseño de software? 🛠️

### Visión detallada
Define la implementación específica de cada módulo o componente:
- Clases y funciones
- Estructuras de datos
- Algoritmos
- APIs
- Patrones de diseño a nivel local

### Plan de implementación
- Guía a los desarrolladores
- Describe interfaces y relaciones
- Define métodos para cumplir requisitos funcionales

### Enfoque práctico
Se centra en aspectos como:
- Corrección del código
- Eficiencia
- Claridad
- Facilidad de mantenimiento

## 3. Arquitectura vs Diseño: Diferencias Clave 📊

| Aspecto              | Arquitectura                                        | Diseño 
|----------------------|-----------------------------------------------------|--------------------------------------------------
| Nivel de abstracción | Alto – esqueleto/fundación del sistema              | Detallado – módulos individuales 
| Pregunta clave       | ¿Qué se construye y dónde?                          | ¿Cómo se construye? 
| Enfoque principal    | Componentes, interacción, calidad del sistema       | Clases, métodos, estructuras de datos, algoritmos 
| Requisitos           | Funcionales + No funcionales (seguridad, escalado…) | Principalmente funcionales 
| Flexibilidad         | Rígido – cambios son costosos                       | Más fácil de cambiar y ajustar 
| Ejemplos             | Microservicios, C4, MVC                             | Singleton, Strategy, Builder, etc. 

La arquitectura establece la estructura general y las decisiones de diseño de sistemas completos, mientras que el diseño detalla las piezas individuales, definiendo módulos concretos y el flujo interno para materializar la visión arquitectónica.

## 4. Roles y Responsabilidades 👤

### Arquitecto de Software
- Define la estructura general del sistema
- Selecciona tecnologías y patrones
- Alinea la arquitectura con objetivos de negocio
- Balancea aspectos de rendimiento, costo y seguridad
- Interactúa con stakeholders
- Documenta decisiones arquitectónicas
- Lidera visiones cross-equipo (Enterprise vs Solution Architect)

### Diseñador / Desarrollador de Software
- Traduce la visión arquitectónica en componentes concretos
- Define clases, interfaces y flujos
- Implementa algoritmos
- Desarrolla pruebas unitarias
- Aplica patrones de diseño (creacional, estructural, comportamental)
- Se enfoca en la calidad del código

## 5. Enfoque Pedagógico para el Aprendizaje 📚

### Ejercicio Comparativo
Toma una aplicación sencilla (por ejemplo, un sistema de blog) y:

#### Para la Arquitectura:
- Identifica componentes principales (frontend, backend, DB)
- Define la comunicación entre componentes
- Establece requisitos de calidad

#### Para el Diseño:
- Diagrama de clases por componente
- Definición de funciones
- Estructuras de datos
- Implementación de patrones de diseño (MVC, Repository, etc.)

### Roles en Práctica
Simula un entorno de trabajo real:

#### Como Arquitecto:
- Define la estructura general
- Crea diagramas de alto nivel (C4)
- Establece criterios de aceptación

#### Como Diseñador:
- Implementa la solución
- Documenta el código
- Desarrolla pruebas

### Ciclo Iterativo
1. Documenta decisiones arquitectónicas (ej. microservicios, CQRS)
2. Justifica las elecciones técnicas
3. Diseña módulos localmente
4. Desarrolla prototipos
5. Evalúa trade-offs
6. Documenta lecciones aprendidas 