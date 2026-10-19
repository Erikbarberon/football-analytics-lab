<div align="center">

# ⚽ Football Analytics Lab
### Sports Science, Quantitative Modeling & BI Dashboards

Un ecosistema modular para el análisis cuantitativo y visualización interactiva de rendimiento en fútbol profesional.  
Cada investigación integra extracción de datos en **Python**, modelado estadístico (*Expected Goals*, varianza, *Game States*) y dashboards en **Chart.js** y **Tailwind CSS**.

---

[![Live Demo](https://img.shields.io/badge/Demo-GitHub%20Pages-059669?style=for-the-badge&logo=githubpages&logoColor=white)](https://<tu-usuario>.github.io/<nombre-repo>/)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Chart.js](https://img.shields.io/badge/Chart.js-4.4-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0+-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

[Dashboard en Vivo](https://erikbarberon.github.io/football-analytics-lab/) • [Dataset Abierto](#-datasets) • [Metodología](#️-stack-tecnológico)

---

</div>

## 📑 Catálogo de Investigaciones

| ID | Proyecto | Foco Analítico | Muestra | Estado | Enlaces |
| :---: | :--- | :--- | :---: | :---: | :---: |
| **01** | **Jürgen Klopp: ¿Caos o Control?** | Sobre-ejecución xG, Efecto Alisson y Varianza | 76 Fechas Premier League | `Completado` | [Dashboard](https://Erikbarberon.github.io/football-analytics-lab/studies/01-liverpool-klopp/index.html) · [Notebook](./studies/01-liverpool-klopp/analysis.ipynb) |
| **02** | **Radar Sub-23: Extremos en Sudamérica** | Scouting predictivo, carreras progresivas y SCA | LPF / Brasileirão / CONMEBOL | `En Desarrollo` | *Próximamente* |
| **03** | **Presión Alta e Intensidad PPDA** | Bloque alto, recuperaciones y peligro generado | Top 5 Ligas Europeas | `Roadmap` | *Próximamente* |

---

## 🔬 Estudio Destacado: Liverpool FC (17/18 vs 19/20)

### *Desmitificando el título de los 99 puntos a través de xG, varianza y estados del partido*

Este estudio compara cuantitativamente dos versiones del Liverpool de Jürgen Klopp: El liverpool del (2017/18) frente al equipo que levantó la Premier League tras 30 años (2019/20).

### Hallazgos Principales:

* **Letalidad Ofensiva (+9.80 G-xG):**  
  En 2019/20 el equipo **no generó más peligro** (su $xG$ cayó de $84.6$ a $75.2$), sino que registró un pico histórico de finalización en Mohamed Salah y Sadio Mané, convirtiendo casi 10 goles por encima de la probabilidad de tiro.
* **El "Efecto Alisson Becker" (-6.60 xGA vs GA):**  
  Pese a conceder $3.8$ unidades más de peligro esperado ($39.6$ vs $35.8$ $xGA$), recibieron 5 goles reales menos. La presencia de Alisson neutralizó situaciones de mano a mano de alto valor.
* **Control del Caos y Varianza ($\sigma: 1.86 \rightarrow 1.56$):**  
  Se redujeron los partidos de marcador desbordado (de 16 a 13 con 4+ goles) y se perfeccionó la administración del marcador una vez en ventaja (*Game States*), logrando **14 victorias por 1 gol de diferencia**.

---
