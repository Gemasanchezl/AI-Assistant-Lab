# AI-Assistant-Lab
A personal lab to explore how generative AI can assist in creative, analytical, and design workflows. Includes spec-driven experiments, workflows, and prototypes built with tools like Cursor, Claude, and Figma.

Project initialized by Gema

---

## 🎯 Atida UX Assistant

**Atida UX Assistant** es un sistema de IA que ayuda a analizar, idear y generar copy de UX para experiencias de ecommerce.

### 📚 Módulos de prompts disponibles

El asistente utiliza los siguientes módulos locales de prompts ubicados en `/prompts/`:

- **`interview-insight-analyzer.md`** — Para analizar investigación cualitativa (entrevistas, feedback de usuarios)
- **`basket-atidacash-analyzer.md`** — Para identificar fricción en la cesta relacionada con Atida Cash
- **`basket-atidacash-ideator.md`** — Para generar ideas de mejora basadas en insights
- **`basket-copy-generator.md`** — Para escribir microcopy y tooltips
- **`copy-validation-checklist.md`** — Para validar tono y claridad del copy

### 🎯 Cómo usar el asistente

El asistente selecciona automáticamente qué módulo(s) usar según tu solicitud:

- **"Analiza este feedback"** → Usa el analyzer
- **"Dame ideas de UX"** → Usa el ideator
- **"Genera texto para tooltip"** → Usa el copy generator
- **"Valida este texto"** → Usa el checklist

Los módulos pueden combinarse cuando sea necesario (ej: analizar → idear → generar copy).

### 🌍 Idioma y tono

- **Idioma:** Todos los outputs están en español natural (España)
- **Tono:** Claro, empático y profesional (estilo Atida)
- **Objetivo:** Facilitar la investigación de UX y la generación de copy de forma más rápida y centrada en el usuario
