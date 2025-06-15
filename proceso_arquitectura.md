# Proceso de Arquitectura

1. Entender los requerimientos del Sistema

   Los requerimientos describen lo que el sistema debe hacer, por lo tanto, definimos tareas a alto nivel, flujos de trabajo, servicios lógicos, e interfaz de usuario.

2. Entender los requerimientos no funcionales del Sistema

   Definen los atributos técnicos y de nivel de servicio del sistema. Son mas complejos estos requerimientos porque suelen implicar mas elementos arquitectonicos.

   - Atributos de calidad (-ilities)
     - Escalabilidad: Scale up (cpu, mem), Scale out (vm, load-balancers, redundancia)
     - Manejabilidad: que pasa dentro del sistema (Monitoreo)
     - Modularidad: piezas moviles, bloques pequeños que suman un todo
     - Extensibilidad: ampliar funcionalidad
     - Testeabilidad: tipos de testing (manual, unitaria, integración)

3. Mapear los Componentes

   Los componentes son las partes moviles del sistema y representan las distintas tareas del sistema. El mapa de componentes tiene 2 objetivos: 1) ayudar a comprender el sistema y 2) comunica al cliente tu comprensión del sistema asegurandole que nada se escapa.

4. Seleccionar el Stack tecnológico

   Decidir junto con el equipo de desarrollo, cual es la plataforma en la que se basará el sisetma. Seleccionar la plataforma backend, frontend y de almacen de datos. Para microservicio puede ser posible usar distintas plataformas backend y de almacen de datos. Elegir racionalmente, el Stack incorrecto puede hacer fracasar todo el sistema.

5. Diseñar la arquitectura

   Con los requisitos funcionales y no funcionales, los componentes y el stack, solo queda aglutinar todos esos elementos que darán como resultado un sistema rápido, seguro, confiable y fácil de mantener.

6. Escribir documento de arquitectura

   El documento edscribe todo el procesos por el que ha pasado y ofrece a los desarrolladores una imagen completa de lo que se va a construir.

7. Apoyo al equipo

   La arquitectura es una criatura viva y cambiante. Hay que trabajar junto con los desarrolladores para asegurarse que se desarrolla de acuerdo a la arquitectura.

   En medio habrá discusiones, dilemas y conversaciones que cambiaran la arquitectura (y no solo una vez).

   El documento no tiene porque ser un pisapapeles glorificado, nunca acabas hasta que el sistema este en producción, y luego de eso habrá mucho mas por hacer.
