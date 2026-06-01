# Auditoría Kany IAC – Test Basado en Papers

Auditoría independiente de Kany IAC (IA argentina) usando 15 preguntas extraídas de benchmarks académicos (GSM8K, MATH, HumanEval, HLE, R-Bench).

🌐 **Ver auditoría interactiva:** https://dariozfold6-wez2.github.io/kany-audit/

📄 **Ver transcript completo:** [transcript-kany.md](./transcript-kany.md)

---

## Resultados clave
- ✅ **15/15** respuestas técnicamente correctas
- 🔶 **2 correcciones al evaluador** (P7 y P14 – detectó errores en el gold standard)
- 🧠 **0 alucinaciones graves**
- ⚡ Razonamiento paso a paso verificable

## Metodología
Preguntas extraídas de papers con revisión por pares:
- **GSM8K** – Cobbe et al., 2021
- **MATH** – Hendrycks et al., 2021  
- **HumanEval** – Chen et al., 2021
- **Humanity's Last Exam** – Phan et al., 2025
- **R-Bench** – Guo et al., 2025
- **Lindley Paradox** – 1957

## Qué demuestra
Kany no solo responde bien: **recalcula y sostiene la corrección** cuando el evaluador se equivoca. Comportamiento típico de modelos top-tier con capacidad de introspección.

---
*Auditoría Mayo 2026 – Buenos Aires – Dario Crespo*
