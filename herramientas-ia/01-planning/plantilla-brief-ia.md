# Plantilla Maestra de Brief para IA

> Copia este archivo por cada tarea. Nunca uses el original directamente.
> Completa todas las secciones antes de enviar el brief a la IA.

---

## Metadata

**Fecha:**
**Proyecto:**
**Tarea #:**

---

## Título de la Tarea

<!-- Una frase que fija el alcance. Debe contener intención técnica, no solo descripción. -->
<!-- Mal: "calcular impuestos" | Bien: "servicio desacoplado de cálculo de impuestos" -->

_[Escribe el título aquí]_

---

## Contexto

<!-- Explica POR QUÉ existe el problema y qué parte del sistema toca.
     Sin este bloque la IA rellena huecos con suposiciones. -->

**Sistema actual / entorno:**
_[Describe el sistema, tecnología, estado actual]_

**Problema que se resuelve:**
_[Qué está fallando, qué es incorrecto, qué necesita cambiar]_

**Objetivo concreto:**
_[Qué debe quedar funcionando al terminar esta tarea]_

---

## Requerimientos Técnicos

<!-- Convierte la intención en especificación operativa.
     Define CÓMO debe implementarse la solución. -->

**Lenguaje / versión:** _[ej. Python 3.11+]_

**Patrón / arquitectura:** _[ej. Strategy Pattern, REST, MVC]_

**Input:** _[tipo y estructura del input]_

**Output:** _[tipo y estructura del output]_

**Integraciones:** _[servicios externos, bases de datos, APIs]_

**Notas adicionales:** _[cualquier especificación técnica que no encaje arriba]_

---

## Constraints

<!-- Lo que la IA NO debe hacer y los estándares que debe respetar.
     Sin este bloque la IA inventa dependencias y simplifica pruebas.
     Ejemplos: sin librerías externas | type hints obligatorios | tests con pytest | linter del proyecto | no modificar archivo X -->

- [ ]
- [ ]
- [ ]
- [ ]
- [ ]

---

## Definition of Done

<!-- Criterios verificables para considerar la tarea terminada.
     No "que funcione", sino evidencia concreta y medible.
     Ejemplos: todos los tests pasan | cobertura > 90% | linter sin warnings | docstrings en interfaz pública -->

- [ ]
- [ ]
- [ ]
- [ ]
- [ ]

---

## Paso 1 — Crítica del Brief

> Antes de pedir código o plan, envía el brief con esta instrucción:

```
Este es mi Technical Brief. Antes de escribir código, critica el brief:
¿qué falta? ¿qué está ambiguo? ¿qué restricción añadirías?
```

**Observaciones recibidas de la IA:**
_[Registra aquí lo que la IA señaló. Actualiza el brief si aplica.]_

---

## Paso 2 — Plan de Implementación

> Una vez el brief esté validado, solicita el plan con esta instrucción:

```
Basado en el brief anterior, genera un plan de implementación paso a paso.
NO escribas código aún. Lista los archivos que crearás, los que modificarás
(y por qué) y la lógica de cada uno en lenguaje natural.
```

**Plan validado:**
_[Pega aquí el plan aprobado. Tacha o anota los ajustes negociados.]_
