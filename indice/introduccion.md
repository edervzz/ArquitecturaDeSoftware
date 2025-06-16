# Introducción a la Arquitectura de Software

## ¿Qué es la arquitectura de software?

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

## ¿Qué es el Desarrollo de software?

### Visión detallada

Define la implementación específica de cada módulo o componente:

- Clases y funciones
- Estructuras de datos
- Algoritmos
- APIs
- Patrones de Desarrollo a nivel local

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

### Arquitectura vs Desarrollo: Diferencias Clave

| Aspecto              | Arquitectura                                        | Desarrollo                                        |
| -------------------- | --------------------------------------------------- | ------------------------------------------------- |
| Nivel de abstracción | Alto – esqueleto/fundación del sistema              | Detallado – módulos individuales                  |
| Pregunta clave       | ¿Qué se construye y dónde?                          | ¿Cómo se construye?                               |
| Enfoque principal    | Componentes, interacción, calidad del sistema       | Clases, métodos, estructuras de datos, algoritmos |
| Requisitos           | Funcionales + No funcionales (seguridad, escalado…) | Principalmente funcionales                        |
| Flexibilidad         | Rígido – cambios son costosos                       | Más fácil de cambiar y ajustar                    |
| Ejemplos             | Microservicios, C4, MVC                             | Singleton, Strategy, Builder, etc.                |

La Arquitectura establece la estructura general y las decisiones de desarrollo de sistemas completos, mientras que el Desarrollo detalla las piezas individuales, definiendo módulos concretos y el flujo interno para materializar la visión arquitectónica.

## Roles y responsabilidades. Arquitecto vs Desarrollador

Un Desarrollador sabe lo que se puede hacer, conoce de tecnológia, la mejor forma de hacer software, usar librerias, BBDD, etc.

Un Arquitector sabe lo que se debe hacer, se asegura de que el diseño edl software implementa los requisitos del sistema, ademas un arquitecto:

- Sabe programar, porque puede crear POCs, probar librerías, BBDD, etc.
- Apoya al equipo de desarrollo, cuando estos necesitan ayuda
- Gana el respeto, si los desarrolladores ven que resuelves problemas y los escuchas.

### Arquitecto de Software

- Define la estructura general del sistema
- Selecciona tecnologías y patrones
- Alinea la arquitectura con objetivos de negocio
- Balancea aspectos de rendimiento, costo y seguridad
- Interactúa con stakeholders
- Documenta decisiones arquitectónicas
- Lidera visiones cross-equipo (Enterprise vs Solution Architect)

### Desarrollador de Software

- Traduce la visión arquitectónica en componentes concretos
- Define clases, interfaces y flujos
- Implementa algoritmos
- Desarrolla pruebas unitarias
- Aplica patrones de Desarrollo (creacional, estructural, comportamental)
- Se enfoca en la calidad del código
