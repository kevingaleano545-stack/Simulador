# Simulador de Planificación de Procesos - SIGET

## Integrantes

* Kevin Galeano
* Sofía Pabon

## Descripción

Este proyecto consiste en un simulador sencillo de planificación de procesos desarrollado en Python para representar el funcionamiento de un planificador de CPU en el contexto del SIGET.

El programa permite simular diferentes procesos y observar los estados por los que pasan durante su ejecución.

## Algoritmos utilizados

El simulador implementa tres algoritmos de planificación:

* **FIFO:** ejecuta los procesos según el orden en que llegan.
* **Round Robin:** asigna turnos de CPU utilizando un quantum.
* **Prioridad:** ejecuta primero los procesos con mayor prioridad.

## Estados de los procesos

Durante la simulación se pueden observar los siguientes estados:

* Nuevo
* Listo
* Ejecutando
* Bloqueado
* Terminado

## Lenguaje

El proyecto fue desarrollado utilizando **Python**.

## Asignatura

**Sistemas Operativos**

Proyecto académico sobre planificación de procesos.
