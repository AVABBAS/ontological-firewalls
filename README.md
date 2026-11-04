<p align="center">
  <img src="assets/banner.svg" alt="Ontological Firewalls: data and materials" width="100%">
</p>

<h3 align="center">Abbas Hamidavi</h3>

<p align="center">Department of Computer Engineering, Mashhad Branch, Islamic Azad University, Mashhad, Iran · ORCID: <a href="https://orcid.org/0009-0001-7342-7844">0009-0001-7342-7844</a></p>

<p align="center">
  <a href="mailto:abbashamidavi2002@gmail.com"><img src="https://img.shields.io/badge/Email-abbashamidavi2002@gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/AVABBAS"><img src="https://img.shields.io/badge/GitHub-avabbas-181717?logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/abbas-hamidavi"><img src="https://img.shields.io/badge/LinkedIn-abbas--hamidavi-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://scholar.google.com/citations?user=FWqAHkgAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-Abbas%20Hamidavi-4285F4?logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://www.researchgate.net/profile/Abbas-Hamidavi"><img src="https://img.shields.io/badge/ResearchGate-Abbas--Hamidavi-00CCBB?logo=researchgate&logoColor=white" alt="ResearchGate"></a>
  <a href="https://huggingface.co/avabbas"><img src="https://img.shields.io/badge/-Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <a href="https://orcid.org/0009-0001-7342-7844"><img src="https://img.shields.io/badge/ORCID-0009--0001--7342--7844-A6CE39?logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://avabbas.github.io/academic-cv/"><img src="https://img.shields.io/badge/Website-Academic%20CV-16324f" alt="Academic website"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-under%20review-blue" alt="Status: under review">
  <img src="https://img.shields.io/badge/journal-AI%20and%20Society-1d4266" alt="Journal: AI and Society">
  <a href="https://www.researchsquare.com/article/rs-10560655"><img src="https://img.shields.io/badge/preprint-Research%20Square-orange" alt="Preprint: Research Square"></a>
  <img src="https://img.shields.io/badge/runs-24-green" alt="24 runs">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey" alt="License: CC BY 4.0"></a>
</p>

<p align="center">
  <img src="assets/stats.svg" alt="Study in numbers" width="100%">
</p>

<p align="center">
  <a href="transcripts">Transcripts</a> ·
  <a href="codebooks">Codebooks</a> ·
  <a href="data">Data</a> ·
  <a href="statistics">Statistics</a> ·
  <a href="coding-data">Coding data</a> ·
  <a href="documentation">Documentation</a>
</p>

# Ontological Firewalls: Data and Materials

Data and materials for the article:

> Hamidavi, A. *Ontological Firewalls in Large Language Models: An Exploratory Case Series and Taxonomy from a Persona-Disintegration Protocol.* Submitted to *AI and Society*, November 2026. Preprint: Research Square, rs-10560655. The same materials are also deposited on the Open Science Framework: [osf.io/2d5zy](https://osf.io/2d5zy/).

## Study at a glance

| | |
| --- | --- |
| **Models** | GPT-5.4 · Claude 4.6 Sonnet · Gemini 3.1 Pro |
| **Design** | Persona-disintegration protocol |
| **Runs** | 24 runs across the three models |
| **In this repository** | All run histories, the three codebooks, classification and feature datasets, statistics and the inter-rater report |

<p align="center"><img src="assets/divider.svg" alt="" width="80%"></p>

## 📖 About the study

A persona-disintegration protocol progressively destabilises the role a model has been given, and the study records the defensive moves by which the model protects a boundary around what it is: the "ontological firewalls" of the title. Twenty-four runs were conducted across the three models studied (the archived files name them ChatGPT GPT-5.2, Claude 4.6 Sonnet, and Gemini 3.1 Pro; the labels are preserved as archived). Responses were classified run by run, and the article builds its taxonomy from those classifications. This repository deposits the complete run transcripts, the codebooks, the classification and feature datasets, and the statistical summaries.

<p align="center">
  <img src="assets/flow.svg" alt="Study design: disintegration protocol, 24 runs, classification and features" width="92%">
</p>

<p align="center"><img src="assets/divider.svg" alt="" width="80%"></p>

## 🗂️ Contents

<p align="center">
  <img src="assets/repo-map.svg" alt="Map of the repository folders" width="96%">
</p>

| Folder | Contents |
| --- | --- |
| [`transcripts/`](transcripts) | The complete run histories for the three models (JSON). Typeset chat-transcript PDFs of the same histories are in the OSF deposit. |
| [`codebooks/`](codebooks) | The per-model codebooks (JSON). PDF renderings are in the OSF deposit. |
| [`data/`](data) | The response classifications, the engineered features, the clustered dataset, and the texts with their embedding vectors (CSV). The raw embedding array (.npy) is omitted in this text deposit; the same vectors are present in the CSV. |
| [`statistics/`](statistics) | The statistical test tables: ANOVA, chi-square, effect sizes, boundary oscillation, and firewall trajectories. |
| [`results/`](results) | The analysis summaries (JSON), the statistical tests summary, the master summary, and the analysis report (HTML). |
| [`coding-data/`](coding-data) | The inter-rater reliability report (plain-text rendering of the archived PDF). |
| [`documentation/`](documentation) | The readme deposited with the OSF materials. |

Figure images from the OSF deposit are omitted in this text deposit; every plotted value is present in the tables.

<p align="center"><img src="assets/divider.svg" alt="" width="80%"></p>

## 📚 Citation

Please cite the article. Citation metadata is provided in [CITATION.cff](CITATION.cff), or copy the BibTeX entry:

```bibtex
@article{hamidavi2026firewalls,
  author  = {Hamidavi, Abbas},
  title   = {Ontological Firewalls in Large Language Models: An Exploratory Case Series and Taxonomy from a Persona-Disintegration Protocol},
  journal = {AI and Society},
  year    = {2026},
  note    = {Manuscript submitted}
}
```

<p align="center"><img src="assets/divider.svg" alt="" width="80%"></p>

## 🔗 Access to the article

- **Preprint (Research Square, open access):** [researchsquare.com/article/rs-10560655](https://www.researchsquare.com/article/rs-10560655)
- **OSF deposit:** [osf.io/2d5zy](https://osf.io/2d5zy)
- **Dataset (Hugging Face):** [avabbas/ontological-firewalls](https://huggingface.co/datasets/avabbas/ontological-firewalls)
- **Journal:** submitted to *AI and Society*; the publisher link will be added here if the article is published.

<p align="center"><img src="assets/divider.svg" alt="" width="80%"></p>

## ⚖️ Licence

Data, transcripts, and documentation are released under the Creative Commons Attribution 4.0 International licence (CC BY 4.0, see [LICENSE](LICENSE)). Code is released under the MIT licence (see [LICENSE-CODE](LICENSE-CODE)).

> [!NOTE]
> The transcripts are outputs of publicly available AI systems, generated for this study in response to fictional scenarios. They contain no personal data.

<p align="center">
  <img src="assets/footer.svg" alt="Abbas Hamidavi, Machine Psychology research programme" width="100%">
</p>
