# 🏗️ Arquitectura de Software

Un arquitecto sabe lo que se debe hacer, por ende esta familiarizado con el desarrollo aunque no es su principal objetivo. Se asegura de que el diseño del software, implementa los requisitos del sistema. Prepara POCs, revisa librerias, DB e investiga sobre patrones y tendencias. Apoya al equipo de desarrollo cuando estos necesitan ayuda, escuchandoles y resolviendo problemas crea un círculo de respeto y aprecio.

- Diseño de la infraestructura (servidores, almacenamiento, on-prem, cloud)
- Familiarizado con requerimientos del cliente
- Plan de carrera enfocado en cloud, infraestructura y seguridad

## Un arquitecto vela por una misión

Todo sistema diseñado por el arquitecto debe cumplir 4 aspectos:

- Rápido
- Seguro
- Confiable
- Fácil de mantener

_Esta lista no tiene relación con patrones de arquitectura o plataformas, esto es porque el arquitecto sabe que la tecnología, patrones y todo lo demás, no son mas que los medios para llegar al resultado final. **La tecnología debe estar al servicio de las necesidades y no al revés.**_

## Mindset: _Entender las necesidades del negocio_

- Siempre tratar de entender las partes internas del negocio
- Que le quita el sueño al usuario
- Puntos debiles y fuertes
- Con quien compiten
- Cual es la estrategia de crecimiento

_Hasta no entender los requerimientos, preocupaciones e intereses del usuario, podremos hablar de arquitectura y tecnológia._

## Proceso de Arquitectura

1. Entender los requerimientos del Sistema
2. Entender los requerimientos no funcionales del Sistema
   - Atributos de calidad (-ilities)
     - Escalabilidad: Scale up (cpu, mem), Scale out (vm, load-balancers, redundancia)
     - Manejabilidad: que pasa dentro del sistema (Monitoreo)
     - Modularidad: piezas moviles, bloques pequeños que suman un todo
     - Extensibilidad: ampliar funcionalidad
     - Testeabilidad: tipos de testing (manual, unitaria, integración)
3. Mapear los Componentes
4. Seleccionar el Stack tecnológico
5. Diseñar la arquitectura
6. Escribir documento de arquitectura
7. Apoyo al equipo

## Índice

- [Introducción a la Arquitectura de Software](introduccion.md)

  - ¿Qué es la arquitectura de software?
  - ¿Qué es el Desarrollo de software?
  - Arquitectura vs Desarrollo: Diferencias Clave
  - Roles y Responsabilidades

- [Principios SOLID](solid.md)

  - Principio de Responsabilidad Única (SRP)
  - Principio Abierto-Cerrado (OCP)
  - Principio de Sustitución de Liskov (LSP)
  - Principio de Segregación de Interfaces (ISP)
  - Principio de Inversión de Dependencias (DIP)
  - Resumen de SOLID](#resumen-de-solid)

- [Estilos Arquitectónicos](estilos_arquitectonicos.md)

  - Monolito)
  - Cliente-Servidor
  - Multicapa
  - MVC
  - Microkernel
  - Comparativa de Estilos

- [Estilos de despliegue](estilos_despliegues.md)
  - Microservicios
  - Serverless
  - Comparativa Microservicios vs Serverless
