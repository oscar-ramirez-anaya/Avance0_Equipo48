<div style="text-align: center;">

# Avance 0 | Propuesta de proyecto y firma de convenios

### Planograma: IA para detección de productos y ubicación

**Tecnológico de Monterrey** · Maestría en Inteligencia Artificial Aplicada
**TC5035.10 — Proyecto Integrador (Grupo 10)**

**Equipo 48** · **Modalidad:** En equipo · **Fecha:** Septiembre 2026

| Integrante | Matrícula |
|---|---|
| Oscar Alberto Ramírez Anaya | A01795438 |
| Germán Eduardo Rodríguez Vázquez | A01796325 |
| Jesús Soto Medrano | A01794746 |

**Profesora:** Dra. Grettel Barceló Alonso · **Asesor:** Dr. Raúl Valente Ramírez
**Sponsor:** Dr. Juan Arturo Nolazco Flores · **Organización:** Bnext

</div>

---

## Descripción

Propuesta del proyecto integrador, fase de *Entendimiento del negocio y de los datos* de la
metodología CRISP-ML(Q). El proyecto busca detectar, a partir de imágenes de anaquel, los productos y
los espacios vacíos, determinar si cada posición está correcta, faltante o mal ubicada respecto al
planograma y generar alertas de resurtido. Se desarrolla con Bnext (Monterrey), empresa de software
para retail, bajo un convenio de confidencialidad.

## Contenido

| Archivo | Descripción |
|---|---|
| **`Avance0.48.pdf`** | Entregable: antecedentes, entendimiento del negocio, entendimiento inicial de los datos y convenios |
| `Avance0.48.html` | Fuente editable del documento |
| `assets/print.css` | Hoja de estilo de impresión (A4) |
| `numerar_paginas.py` | Estampa el pie de página y los metadatos sobre el PDF |

## Secciones del documento

1. **Antecedentes:** la organización, el proceso de negocio impactado (resurtido y cumplimiento de
   planograma) y la metodología CRISP-ML(Q).
2. **Entendimiento del negocio:** formulación del problema, contexto, objetivos, criterios de éxito,
   preguntas clave e involucrados.
3. **Entendimiento de los datos:** descripción inicial del conjunto de imágenes, técnica de
   aprendizaje automático y variables de entrada y salida.
4. **Convenios.**

## Regenerar el PDF

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless --disable-gpu --no-pdf-header-footer \
  --print-to-pdf="Avance0.48.pdf" "file://$(pwd)/Avance0.48.html"
python3 numerar_paginas.py
```

## Convenio de confidencialidad

El NDA firmado por los integrantes no se incluye por su carácter confidencial; el sponsor y el asesor
tienen conocimiento de su firma.
