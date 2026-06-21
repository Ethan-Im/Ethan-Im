content = '''<div align=\"center\">
  <img src=\"https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:00ff88&height=220&section=header&text=Ethan%20Im&fontSize=48&fontColor=00ff88&animation=fadeIn&fontAlignY=40&desc=AI%20Researcher%20×%20Computational%20Drug%20Discovery&descColor=888888&descAlignY=65\" width=\"100%\"/>
</div>

<div align=\"center\">
  <img src=\"https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00FF88&center=true&width=600&lines=9+Years+Chemical+Engineer+%40+Henkel;Chemistry+%2B+CS+%2B+AI;Building+EGFR-Inverse+%F0%9F%A7%AC;Inverse+Molecular+Design+for+Drug+Discovery\" />
</div>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ethan-im-68335930a)
[![Threads](https://img.shields.io/badge/Threads-000000?style=for-the-badge&logo=threads&logoColor=white)](https://www.threads.com/@ethan.im_)

<br/>

\`\`\`python
ethan = {
    \"role\"    : \"Chemical Engineer → AI Researcher\",
    \"focus\"   : \"Inverse molecular design for drug discovery & materials\",
    \"stack\"   : [\"PyTorch\", \"PyTorch Geometric\", \"AttentiveFP\", \"RDKit\", \"Genetic Algorithms\"],
    \"mission\" : \"Accelerate drug & materials discovery with AI\",
    \"belief\"  : \"SF should become reality 🚀\"
}
\`\`\`

<br/>

## 🧬 EGFR-Inverse — Flagship Project

> *\"Design EGFR inhibitors — including for drug-resistant cancer mutations — with AI, end to end.\"*

[![Demo](https://img.shields.io/badge/🔬_Live_Demo-00ff88?style=for-the-badge)](https://github.com/Ethan-Im/EGFR-Inverse)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/Ethan-Im/EGFR-Inverse)
[![Research Notes](https://img.shields.io/badge/Research_Notes-blue?style=for-the-badge)](https://github.com/Ethan-Im/EGFR-Inverse/tree/main/research_notes)

ChEMBL bioactivity data → AttentiveFP GNN → Genetic Algorithm inverse design, extended into a comparative study of wild-type vs. T790M drug-resistant EGFR.

| Model | Train n | Test R | Test R² |
|-------|---------|--------|---------|
| Wild-type EGFR | 14,098 | **0.736** | 0.534 |
| T790M (real only) | 1,552 | 0.400 | 0.155 |
| T790M (+ pseudo-labeling) | 13,900 | **0.698** 🔄 | 0.487 |

**Central research question:** does limited mutant-specific data degrade not just affinity prediction, but the trustworthiness of AI-generated drug candidates — and can pseudo-labeling close that gap? *(in progress)*

16 novel wild-type EGFR inhibitor candidates generated (predicted pChEMBL > 10.0, SA Score ≤ 4.0, QED ≥ 0.4, Lipinski-compliant).

<br/>

## 🔭 Other Research

<table>
<tr>
<td width=\"50%\" valign=\"top\">

### 🧪 Polyinverse
*\"Tell the AI what properties you want. It designs the molecule.\"*

[![Demo](https://img.shields.io/badge/🤗_Live_Demo-00ff88?style=flat-square)](https://huggingface.co/spaces/Ethan-Im/polyinverse)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Ethan-Im/polyinverse)

GNN-based polymer property prediction & inverse design. PI1M pseudo-labeling lifted Tg R² from 0.373 → 0.793.

| Property | R² |
|----------|----|
| Density  | **0.871** ✅ |
| Tc       | **0.728** ✅ |
| Tg       | **0.793** ✅ |

</td>
<td width=\"50%\" valign=\"top\">

### 🔋 Battery-AI
*Predicting & inverse-designing solid-state electrolytes.*

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Ethan-Im/Battery-Ai)

Ionic conductivity prediction (606 compounds, Materials Project + OBELiX) via XGBoost + CatBoost ensemble.

| Metric | Score |
|--------|-------|
| R² | **0.775** ✅ |
| MAE | 0.954 |

16 novel solid-electrolyte candidates proposed (top: Li₅BrP₂ClS₄).

</td>
</tr>
</table>

<br/>

<div align=\"center\">
  <img src=\"https://streak-stats.demolab.com?user=Ethan-Im&theme=tokyonight&hide_border=true&background=0d1117&ring=00ff88&fire=00ff88&currStreakLabel=00ff88\" height=\"150\"/>
</div>

<div align=\"center\">
  <img src=\"https://github-readme-activity-graph.vercel.app/graph?username=Ethan-Im&theme=react-dark&bg_color=0d1117&color=00ff88&line=00ff88&point=ffffff&hide_border=true\" width=\"100%\"/>
</div>

<div align=\"center\">
  <img src=\"https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Ethan-Im&theme=tokyonight\" height=\"150\"/>
</div>
