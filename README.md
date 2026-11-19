# 🛡️ Anonimizador de Datos — RGPD/LOPDGDD

**👉 Usar la aplicación: https://cjgaland.github.io/anonimizador-rgpd-web/**

Aplicación gratuita para pseudonimizar y anonimizar datos personales conforme
al RGPD y la LOPDGDD. **Una sola aplicación**: arrastras tu archivo y se abre la
herramienta que le corresponde.

- **Tablas de datos** (`.xlsx`, `.csv`, `.ods`)
- **Documentos PDF** (texto digital y escaneados con OCR)
- **Documentos Word** (`.docx`)
- **Comprobar la integridad** de cualquier fichero con su huella digital
- **Tabla de correspondencia** cifrada, para revertir una seudonimización

Lo que sigue describe la herramienta de tablas de datos.

## ¿Qué hace?

Sustituye los datos sensibles de tus columnas (nombres, DNI, teléfonos,
direcciones, diagnósticos, etc.) por valores ficticios, enmascarados,
generalizados o eliminados — tú eliges el modo por cada columna — mientras
conserva intacto todo lo demás: formato, estilos, fórmulas y el resto de
columnas sin tocar.

- 6 modos de anonimización por columna (datos ficticios, enmascarado, hash,
  generalización, sustitución, supresión)
- Detección automática de columnas sensibles y de categorías especiales
  (art. 9 RGPD: salud, religión, biometría…)
- Detección de PII infiltrada en columnas de texto libre, con revisión
  interactiva antes de aplicar
- Cálculo real de k-anonimato sobre el resultado
- Informe de cumplimiento con diseño, listo para imprimir o guardar en PDF
- Coherencia referencial: el mismo dato original recibe siempre el mismo
  valor ficticio, incluso entre varias hojas o archivos

## 🔒 Privacidad

**Todo el procesamiento ocurre en tu navegador.** Ningún archivo ni dato sale
de tu equipo: no hay servidor, no hay subida de ficheros, no hay cookies ni
trazas. Puedes verificarlo tú mismo — es una única página HTML, sin backend,
cuyo código puedes inspeccionar en este mismo repositorio.

## 📌 Instalar como app (macOS / iOS)

En Safari, usa **Archivo → Añadir al Dock** (macOS) o **Compartir → Añadir a
pantalla de inicio** (iOS/iPadOS) para tener el Anonimizador como una app
independiente, con su propio icono.

## ⚖️ Aviso

Esta herramienta es una medida técnica en el sentido de los arts. 25 y 32
RGPD. No sustituye la valoración jurídica de la base de tratamiento (art. 6)
ni la evaluación del riesgo residual (art. 24) — esa responsabilidad es
siempre del responsable del tratamiento.

---
Aplicación creada y diseñada por **Carlos J. Galán Doval** · 2026
