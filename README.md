# purfa-android
PUerta con Reconocimiento FAcial - Repositorio de la app Android

##Introducción

Purfa es una puerta con reconocimiento facial realizada para la asignatura de Sistemas operativos avanzados en la Universidad Nacional de La Matanza, Argentina.
El sistema reconoce los usuarios que pasan frente a la puerta, y se traba o se destraba dependiendo de los permisos del usuario reconocido.

## Arquitectura

La arquitectura del sistema consiste de tres partes.

1. **Servidor:** El backend realizado en node.js está encargado de sincronizar el sistema embebido con la aplicación mobile. 
2. **App mobile:** La app mobile realizada en Android (Java) se encarga del enroll de los usuarios, controlar la puerta remotamente, habilitar/deshabilitar el sistema de reconocimiento automático, ver historiales de uso y asignar y revocar permisos a usuarios.
3. **Sistema embebido:** El sistema embebido realizado con Arduino (Processing) está montado sobre una puerta y utiliza como sensores una cámara, un botón y un sensor de movimiento y como actuadores un motor y dos luces, una verde (éxito) y una roja (fracaso).

## App mobile - Android

## Acerca de nosotros

El grupo de trabajo está integrado por:

* **Nahuel Roldán.** [Linkedin](https://www.linkedin.com/in/nahuel-rold%C3%A1n-4a52143a)
* **Agustín Bravo.** [Linkedin](https://www.linkedin.com/in/agustin-bravo-b23ab458)
* **Fernando Ortiz.** [Linkedin](https://www.linkedin.com/in/fernando-mart%C3%ADn-ortiz-77649167)
