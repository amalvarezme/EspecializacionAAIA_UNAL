# Especialización en Aprendizaje Automático mediante Inteligencia Artificial

Página informativa para aspirantes al programa de posgrado de la **Universidad Nacional de Colombia — Sede Manizales**, Facultad de Ingeniería y Arquitectura, Departamento de Ingeniería Eléctrica, Electrónica y Computación.

🔗 **https://amalvarezme.github.io/EspecializacionAAIA_UNAL/**

## El programa

| | |
|---|---|
| Código SNIES | 118852 |
| Título | Especialista en Aprendizaje Automático mediante Inteligencia Artificial |
| Duración | 2 periodos académicos |
| Créditos | 28 (16 obligatorios + 12 elegibles) |
| Modalidad | Presencial mediada por TIC |
| Campus | La Nubia, Manizales |
| Primera cohorte | 2027-I |

## Contenido de la página

- Ficha del registro oficial, objetivos y perfiles de ingreso y egreso.
- Proceso de admisión y estructura de costos en puntos.
- **Diagrama de flujo del plan de estudios**: las cuatro obligatorias como cadena de producción (datos → modelo → profundización → despliegue), con las elegibles conectadas al punto de la cadena donde realmente entran.
- Resumen de las 11 asignaturas y su relación con perfiles de *AI engineering* y *forward deployed engineering*.
- Capacidades de trabajo local y sobre sistemas embebidos.
- Factor diferenciador frente a la oferta nacional.

## Fuentes

Toda la información proviene del registro oficial del programa y del Régimen Legal de la Universidad Nacional de Colombia:

| Norma | Contenido |
|---|---|
| Acuerdo 010 de 2025 — Consejo de Sede Manizales | Creación y apertura del programa |
| Acuerdo 013 de 2025 — Consejo de Sede Manizales | Estructura curricular vigente (28 créditos) |
| Acuerdo 008 de 2026 — Consejo de Sede Manizales | Corrección de la denominación del título |
| Acuerdo 019 de 2026 — Consejo de Facultad de Ingeniería y Arquitectura | Derechos académicos: 125 puntos |
| Acuerdo 020 de 2026 — Consejo de Facultad de Ingeniería y Arquitectura | Reglamento del proceso de admisión |

Registro del programa: [posgrados.unal.edu.co](https://posgrados.unal.edu.co/programa/?id=669) · Normativa: [legal.unal.edu.co](https://legal.unal.edu.co/rlunal/home/)

## Estructura técnica

Sitio estático de un solo archivo. Sin build, sin dependencias, sin JavaScript.

```
index.html    página completa (HTML + CSS embebido + diagrama en SVG)
.nojekyll     desactiva el procesamiento Jekyll de GitHub Pages
```

Tipografías servidas desde Google Fonts (Inter e IBM Plex Mono). El diseño sigue el sistema visual del [Laboratorio de Inteligencia Artificial — LIA-UNAL](https://amalvarezme.github.io/LaboratorioIA_UNAL/) y se adapta a tema claro y oscuro según la preferencia del visitante.

### Desarrollo local

```bash
python3 -m http.server 8000
# http://localhost:8000
```

### Despliegue

Automático: cada `push` a `main` actualiza GitHub Pages.

## Contacto

**Andrés Marino Álvarez Meza, Ph.D.** — Director del programa
amalvarezme@unal.edu.co · Campus La Nubia, Km 7 vía al Magdalena, Manizales

---

Los valores de matrícula se liquidan en puntos y el valor del punto es fijado anualmente por la Universidad. Verifique cupos, fechas y costos vigentes en la convocatoria correspondiente.
