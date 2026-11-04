# Ontological Firewalls: Data and Materials

Data and materials for the article:

> Hamidavi, A. *Ontological Firewalls in Large Language Models: An Exploratory Case Series and Taxonomy from a Persona-Disintegration Protocol.* Submitted to *AI and Society*, November 2026. Preprint: Research Square, rs-10560655. The same materials are also deposited on the Open Science Framework: [osf.io/2d5zy](https://osf.io/2d5zy/).

## About the study

A persona-disintegration protocol progressively destabilises the role a model has been given, and the study records the defensive moves by which the model protects a boundary around what it is: the "ontological firewalls" of the title. Twenty-four runs were conducted across the three models studied (the archived files name them ChatGPT GPT-5.2, Claude 4.6 Sonnet, and Gemini 3.1 Pro; the labels are preserved as archived). Responses were classified run by run, and the article builds its taxonomy from those classifications. This repository deposits the complete run transcripts, the codebooks, the classification and feature datasets, and the statistical summaries.

## Contents

| Folder | Contents |
| --- | --- |
| `transcripts/` | The complete run histories for the three models (JSON). Typeset chat-transcript PDFs of the same histories are in the OSF deposit. |
| `codebooks/` | The per-model codebooks (JSON). PDF renderings are in the OSF deposit. |
| `data/` | The response classifications, the engineered features, the clustered dataset, and the texts with their embedding vectors (CSV). The raw embedding array (.npy) is omitted in this text deposit; the same vectors are present in the CSV. |
| `statistics/` | The statistical test tables: ANOVA, chi-square, effect sizes, boundary oscillation, and firewall trajectories. |
| `results/` | The analysis summaries (JSON), the statistical tests summary, the master summary, and the analysis report (HTML). |
| `coding-data/` | The inter-rater reliability report (plain-text rendering of the archived PDF). |
| `documentation/` | The readme deposited with the OSF materials. |

Figure images from the OSF deposit are omitted in this text deposit; every plotted value is present in the tables.

## Citation

Please cite the article. Citation metadata is provided in [CITATION.cff](CITATION.cff).

## Licences

Data, transcripts, and documentation are released under the Creative Commons Attribution 4.0 International licence (CC BY 4.0, see [LICENSE](LICENSE)). Code is released under the MIT licence (see [LICENSE-CODE](LICENSE-CODE)).

The transcripts are outputs of publicly available AI systems, generated for this study in response to fictional scenarios. They contain no personal data.

## Contact

Abbas Hamidavi
Department of Computer Engineering, Mashhad Branch, Islamic Azad University, Mashhad, Iran
ORCID: [0009-0001-7342-7844](https://orcid.org/0009-0001-7342-7844)
