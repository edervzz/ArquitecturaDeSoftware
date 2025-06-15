# Atributos de calidad

Capacidades técnicas que deben ser usadas para completar los requerimientos no funcionales.

## Escalabilidad

Agregar recursos de computo sin alguna interrupción.

- Los sistemas que no son escalables suelen tener piezas de código que no soportan cargas altas y probablemente habrá que reescribir código y reforzar con mas CPU y memoria. Proceso largo y engorroso.

- En cambio los sistemas escalables solo requiren añadir un VM y notificar al balanceador de cargas. No hay cambios al código.

| Scale Up   | Scale Out             |
| ---------- | --------------------- |
| +CPU, +MEM | +VM (LB, redundancia) |

## Manejabilidad

Capacidad de gestionar la aplicación.

Saber que esta pasando con la aplicación en un momento dado y tomar acciones para que mejore su funcionamiento.

Mod
