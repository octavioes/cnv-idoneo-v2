# Simulador Examen de Idoneidad CNV

Simulador de práctica para el examen de idoneidad de la **Comisión Nacional de Valores (CNV)** de Argentina.

🔗 **[idoneocnv.com](https://idoneocnv.com)**

---

## ¿Qué es?

Una aplicación web de página única (HTML) que permite practicar para el examen de idoneidad requerido para operar en el mercado de capitales argentino. El simulador replica la mecánica del examen real: preguntas multiple choice, timer, y corrección inmediata.

## Características

- **681 preguntas** extraídas de la Guía de Estudio oficial publicada por la CNV
- **6 módulos** del programa oficial del examen:
  - Módulo 1 — Marco normativo / Emisoras / OPA / Oferta Pública
  - Módulo 2 — Prevención de Lavado de Activos y Financiamiento del Terrorismo
  - Módulo 3 — Transparencia / Denuncias / Régimen Informativo / Gobierno Corporativo
  - Módulo 4 — Parámetros de análisis de inversión / NIIF / Auditoría
  - Módulo 5 — Agentes / Instrumentos / Operaciones / Derivados
  - Módulo 6 — Fondos Comunes de Inversión / Fideicomisos Financieros
- **Selección flexible**: practicá por módulo individual o examen completo
- **Cantidad configurable** de preguntas por simulacro (5 a 80)
- **Orden aleatorio** de preguntas y opciones de respuesta
- **Timer** con alerta visual cuando queda poco tiempo
- **Feedback inmediato** por pregunta con la respuesta correcta
- **Pantalla de resultados** con porcentaje, desglose y revisión de errores
- **Responsive**: funciona en desktop, tablet y móvil
- **Sin dependencias externas**: un solo archivo HTML autocontenido

## Stack técnico

- HTML5 / CSS3 / JavaScript vanilla
- Fuentes: [Syne](https://fonts.google.com/specimen/Syne) + [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono)
- Google Analytics GA4
- Hosting: Cloudflare Pages

## Uso local

Simplemente abrí `index.html` en cualquier navegador. No requiere servidor, build ni instalación.

```bash
git clone https://github.com/octavioes/idoneocnv.git
cd idoneocnv
open index.html
```

## Fuente de las preguntas

Las preguntas fueron extraídas de la **Guía de Estudio del Examen de Idoneidad** publicada por la CNV en su [sitio web oficial](https://www.cnv.gov.ar). Las opciones de respuesta múltiple fueron elaboradas con fines de práctica.

> Este simulador **NO** constituye material oficial de la CNV, **NO** cuenta con el aval ni la autorización del organismo, y su uso es complementario al estudio de la bibliografía obligatoria.

### Bibliografía oficial de referencia

- [Programa y Bibliografía del Examen (PDF)](https://www.argentina.gob.ar/sites/default/files/programa_bibliografia_examen_idoneo_2025.pdf)
- [Guía de Inscripción al Examen](https://www.argentina.gob.ar/servicio/rendir-el-examen-de-idoneidad)
- [Normas CNV (T.O. 2013)](https://www.cnv.gov.ar/sitioWeb/MarcoRegulatorio)
- [Ley 26.831 de Mercado de Capitales](https://www.argentina.gob.ar/normativa/nacional/ley-26831-206592)

## Estructura del examen real

| | Examen Total | Examen Parcial |
|---|---|---|
| Preguntas | 60 multiple choice | 30 multiple choice |
| Módulos | 6 (10 preguntas c/u) | Según corresponda |
| Duración | 45 minutos | 23 minutos |
| Aprobación | 70% (42 correctas) | 70% (21 correctas) |

## Contribuciones

Si encontrás errores en las preguntas, opciones de respuesta, o tenés sugerencias:

- Abrí un [Issue](../../issues)
- Escribí a **soporte@idoneocnv.com**

## Licencia

MIT

---

☕ **[Invitame un café](https://cafecito.app/octavioesc)** si te resultó útil para preparar el examen.
