# Protocolo de Review — Código Generado por IA

> Copia este archivo por cada tarea. Aplica antes de cada commit con código generado o modificado por IA.
> Para cada ítem marca: ✅ OK | ⚠️ Riesgo bajo | ❌ Corregir: [descripción]

---

## Metadata

**Fecha:**
**Tarea #:**
**Brief referenciado:**

---

## Punto 1 — Alucinaciones de Librerías

**Pregunta clave:** ¿Todos los imports y dependencias realmente existen?

- [ ] ✅/⚠️/❌ ¿El import existe en el ecosistema del proyecto?
- [ ] ✅/⚠️/❌ ¿La librería tiene repositorio activo y mantenido?
- [ ] ✅/⚠️/❌ ¿Las funciones usadas existen en la versión instalada?
- [ ] ✅/⚠️/❌ ¿La dependencia es compatible con el entorno actual?

**Qué revisar:** documentación oficial, repositorio del paquete, compatibilidad con el entorno.

---

## Punto 2 — Lógica de Negocio

**Pregunta clave:** ¿La lógica es correcta en todos los escenarios, incluyendo los bordes?

- [ ] ✅/⚠️/❌ ¿Se usan tipos correctos para cálculos financieros? (evitar `float`)
- [ ] ✅/⚠️/❌ ¿Los redondeos y precisiones son correctos?
- [ ] ✅/⚠️/❌ ¿Las condiciones cubren casos límite (0, null, negativo, máximo)?
- [ ] ✅/⚠️/❌ ¿Las fórmulas críticas fueron verificadas manualmente?
- [ ] ✅/⚠️/❌ ¿Se contempló el caso de entrada vacía o inesperada?

**Qué revisar:** fórmulas críticas, condiciones límite, casos edge.

---

## Punto 3 — Seguridad

**Pregunta clave:** ¿El código es seguro aunque funcione correctamente?

- [ ] ✅/⚠️/❌ ¿Hay riesgo de SQL Injection en queries construidas con strings?
- [ ] ✅/⚠️/❌ ¿Hay riesgo de Command Injection en llamadas al sistema?
- [ ] ✅/⚠️/❌ ¿Todos los inputs externos están validados antes de procesarse?
- [ ] ✅/⚠️/❌ ¿No hay credenciales, tokens o secrets hardcodeados?
- [ ] ✅/⚠️/❌ ¿Los logs no exponen información sensible?
- [ ] ✅/⚠️/❌ ¿Los endpoints requieren autenticación si corresponde?

**Qué revisar:** inputs sin validación, credenciales expuestas, manejo incorrecto de autenticación.

---

## Punto 4 — Pérdida de Contexto

**Pregunta clave:** ¿El código respeta el brief original y el plan validado?

- [ ] ✅/⚠️/❌ ¿Se respetaron todos los constraints del brief?
- [ ] ✅/⚠️/❌ ¿Los tipos e interfaces coinciden con lo definido en el plan?
- [ ] ✅/⚠️/❌ ¿No se modificaron archivos que debían quedar intactos?
- [ ] ✅/⚠️/❌ ¿La estructura de archivos sigue el plan aprobado?
- [ ] ✅/⚠️/❌ ¿La solución cumple todos los criterios de la Definition of Done?

**Qué revisar:** dependencias permitidas, estructura esperada, reglas del proyecto.

---

## Punto 5 — Stack del Proyecto (personalizable)

**Pregunta clave:** ¿El código cumple los estándares específicos de este proyecto?

<!-- Completa estos ítems con los criterios reales de tu stack.
     Ejemplos útiles:
     - ¿Los tests nuevos realmente ejecutan el código nuevo (no son mocks vacíos)?
     - ¿El linter del proyecto pasa sin warnings?
     - ¿No se registran datos sensibles en logs de producción?
     - ¿El código respeta la arquitectura de capas del proyecto? -->

- [ ] ✅/⚠️/❌ _[Criterio de tu stack 1]_
- [ ] ✅/⚠️/❌ _[Criterio de tu stack 2]_
- [ ] ✅/⚠️/❌ _[Criterio de tu stack 3]_

**Ejemplos por stack:** tests que ejecutan código real | linter sin warnings | sin datos sensibles en logs | arquitectura de capas respetada.

---

## Paso Final — Auto-review por la IA (obligatorio)

> Independientemente del resultado de los puntos anteriores, aplica siempre este paso:

```
Revisa tu propio código usando este protocolo:
1. ¿Hay imports o funciones inventadas?
2. ¿La lógica de negocio tiene casos borde sin cubrir?
3. ¿Existe algún riesgo de seguridad?
4. ¿Se respetaron todos los constraints del brief original?
5. ¿El código cumple los estándares del stack del proyecto?
Razona paso a paso y lista cualquier inconsistencia que encuentres.
```

**Hallazgos del auto-review:**
_[Registra aquí lo que la IA reportó. Si no encontró nada, documéntalo igual.]_

---

## Resultado Final

**Revisado por:**
**Decisión:** _[ ] Listo para commit_ | _[ ] Requiere correcciones_

**Hallazgos:**
- Punto 1 (Librerías):
- Punto 2 (Lógica):
- Punto 3 (Seguridad):
- Punto 4 (Contexto):
- Punto 5 (Stack):

**Correcciones pendientes:**
_[Lista los ítems marcados ❌ y cómo se resolvieron antes del commit]_
