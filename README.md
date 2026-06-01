# Auditoría Kany IAC – Test Basado en Papers

Auditoría independiente de **Kany IAC** (IA argentina de Dario Crespo) usando 15 preguntas extraídas directamente de benchmarks académicos.

## Metodología
Cada pregunta está trazada a su paper original, sin modificaciones:
- **GSM8K** (Cobbe et al., 2021) – razonamiento matemático
- **MATH** (Hendrycks et al., 2021) – competición matemática
- **HumanEval** (Chen et al., 2021) – generación de código
- **Humanity's Last Exam** (Phan et al., 2025) – nivel posgrado
- **R-Bench** (Guo et al., 2025) – razonamiento complejo
- **Lindley Paradox** (1957) – estadística bayesiana

## Resultados clave
- ✅ **15/15** respuestas técnicamente correctas
- 🔶 **2 correcciones al evaluador** (el modelo detectó errores en el "gold standard")
    - Q7: Sistema cúbico → $f(-1) = -23$ (no -1)
    - HLE-2: Pozo cuántico → $E_2 = 4\pi^2\hbar^2/2mL^2$ (no $5\pi^2$)
- 🧠 **0 alucinaciones graves**
- 📊 Nivel consistente con frontier models (Gemini 3 Pro: 37.5% HLE, o1: 53.2% R-Bench)

## Qué demuestra
No es solo que responda bien. Kany **recalcula y sostiene la corrección** cuando la premisa del evaluador es incorrecta — comportamiento raro en LLMs que tienden a alinearse.

## Ver auditoría interactiva
Abrí `index.html` o visitá la GitHub Page.

## Referencias
1. Cobbe et al. (2021). Training Verifiers to Solve Math Word Problems. arXiv:2110.14168
2. Hendrycks et al. (2021). Measuring Mathematical Problem Solving With the MATH Dataset. arXiv:2103.03874
3. Chen et al. (2021). Evaluating Large Language Models Trained on Code. arXiv:2107.03374
4. Phan et al. (2025). Humanity's Last Exam. arXiv:2501.14249
5. Guo et al. (2025). R-Bench. arXiv:2505.02018
6. Lindley (1957). A Statistical Paradox. Biometrika 44:187-192

---
*Auditoría realizada Mayo 2026 – Buenos Aires, Argentina*
