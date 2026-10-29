# From Epistemic Injustice to Epistemic Awareness (EpIEpA)

**Process-based methodological research on abuse against adult women in the Catholic Church**

[![Project website](https://img.shields.io/badge/Project-Website-blue)](https://missbrauchsmuster.de/forschen/projekte/forschungsprojekt-von-epistemic-injustice-zu-epistemic-awareness-prozessbasierte-methodenforschung-zu-missbrauch-an-erwachsenen-frauen-in-der-katholischen-kirche/)

# About the project

The research project **“From Epistemic Injustice to Epistemic Awareness: Process-based Methodological Research on Abuse against Adult Women in the Catholic Church”** investigates how sexual abuse against adult women in the Catholic Church is represented, communicated, and made visible—or remains hidden—in written sources.

Research on abuse against adult women in the Catholic Church has so far relied predominantly on interviews with survivors. Written sources, including archival documents, media reports, and online discussions, pose particular methodological challenges: experiences of abuse may be obscured by patriarchal structures of knowledge, and survivors' accounts may not be recognized or interpreted as reports of abuse.

Drawing on Miranda Fricker's concept of *epistemic injustice*, the project investigates the **hidden patterns** that shape how abuse is perceived, whose experiences are acknowledged, and whose knowledge remains invisible.

The project brings together researchers in Media Informatics and Catholic Theology at the University of Regensburg. It combines methodological research in the humanities and social sciences with computational approaches to the identification and analysis of relevant written sources.

### Project information

- **Official project title:** Von Epistemic Injustice zu Epistemic Awareness. Prozessbasierte Methodenforschung zu Missbrauch an erwachsenen Frauen in der katholischen Kirche
- **Short name:** EpIEpA
- **Funding:** German Research Foundation (Deutsche Forschungsgemeinschaft, DFG)
- **DFG project number:** [539293243](https://gepris.dfg.de/)
- **Project period:** April 1, 2025 – March 31, 2028
- **Institution:** University of Regensburg, Germany
- **Project lead:** Prof. Dr. Ute Leimgruber / Prof. Dr. Christian Wolff

For further information, see the [official project page on Missbrauchsmuster](https://missbrauchsmuster.de/forschen/projekte/forschungsprojekt-von-epistemic-injustice-zu-epistemic-awareness-prozessbasierte-methodenforschung-zu-missbrauch-an-erwachsenen-frauen-in-der-katholischen-kirche/).

## Research objectives

The project has two closely connected research strands.

### 1. Computational methods and machine learning

The computational strand develops supervised machine-learning approaches to identify relevant written sources and passages that may otherwise be difficult to find. It also investigates how annotated material can be structured and made accessible for research.

This includes:

- Developing an annotation scheme for identifying relevant patterns in written accounts.
- Creating annotated data for computational analysis.
- Training and evaluating supervised machine-learning models (AI).
- Investigating the strengths and limitations of automated classification.
- Analyzing and visualizing annotation and classification results.

### 2. Epistemic injustice and theological interpretation

The theological strand develops a differentiated methodological approach based on the concept of epistemic injustice, particularly the work of Miranda Fricker.

It examines how knowledge about abuse is expressed, obscured, contested, or rendered invisible in written sources, and how these processes can inform the interpretation of textual material.

Together, these strands aim to develop a more reflective and methodologically transparent approach to researching abuse against adult women in the Catholic Church.

## Repository contents

This repository documents the computational and annotation-related work conducted within the EpIEpA project. It provides access to the research materials made available for reuse and inspection.

The repository is organized around the following resources:

| Resource | Description |
| --- | --- |
| `annotations/` | Annotated texts or excerpts, subject to data protection and publication restrictions. |
| `annotation_analysis/` | Annotation exports, aggregated results and visualizations. |
| `annotation-guidelines/` | Guidelines describing the annotation process and decision rules, annotation schemes, translations of annotation categories. |
| `machine_learning/` | Data, results, prompts and additional material for the machine learning (AI) components. |
| `supplementary_material_publications/` | Supplementary materials and references to related publications. |
| `README.md` | Project overview and repository documentation. |

### Annotations

The annotation data supports the systematic investigation of textual passages relevant to the research questions of EpIEpA.

We distribute the original CATMA annotations alongside adjusted annotation versions for working purposes.

**Data availability:** Only materials explicitly approved for public release is distributed through this repository. 


### Annotation guidelines

The annotation guidelines describe the procedures used to label textual material. They are intended to support transparency, reproducibility, and critical assessment of the annotation process.

The guidelines document the definitions of the annotation categories, inclusion and exclusion criteria, decision rules, and examples used to resolve ambiguous cases.

See [`annotation-guidelines/`](annotation-guidelines/) for the available documentation.

### Annotation analysis results

The repository may include descriptive statistics, annotation distributions and figures.

These materials provide insight into the characteristics of the annotated data and the performance and limitations of computational approaches.

See [`annotation_analysis/`](annotation_analysis/) for available results and visualizations.

### Machine Learning

In this folder, we present data, evaluation results and AI models trained and used in the EpIEpA project. We differentiate between the task of 
- Relevance Detection, meaning the detection of relevant passages in texts
- Fine-grained classification, meaning the classification of annotation categories according to the annotation guidelines

See [`machine_learnings/`](machine_learning/) for all AI-related data.

### supplementary_material_publications

Additional material connected to publications, e.g. posters, presentations, annotation examples etc.

## Methodological considerations and responsible use

Research on sexual abuse requires particular care when collecting, annotating, analyzing, and publishing textual material.

The resources in this repository should be interpreted in light of the project's research questions, annotation methodology, and the limitations of the available sources.

In particular:

- **Context matters.** An annotation represents a methodological interpretation of a text, not necessarily an independently verified account of an event.
- **Machine-learning predictions are not evidence of abuse.** Automated classifications are research tools and require contextual interpretation.
- **Absence of evidence is not evidence of absence.** The failure to identify a relevant passage does not establish that abuse did not occur.
- **Sensitive information must be protected.** Personal data and potentially identifying details must be handled in accordance with applicable legal and ethical requirements.
- **Research materials have limitations.** Source selection, annotation decisions, class distributions, and model performance can influence the results.

The repository is intended for scholarly research and methodological scrutiny. Its materials should not be used to make unsubstantiated allegations about identifiable individuals.

The project is conducted at the University of Regensburg, Germany.

- **Prof. Dr. Ute Leimgruber** — Project lead
- **Magdalena Hürten** — Catholic Theology
- **Thomas Schmidt** — Media Informatics
- **Prof. Dr. Christian Wolff** — Media Informatics

For general inquiries, please contact:

**Thomas Schmidt**  
Email: [thomas.schmidt@ur.de](mailto:thomas.schmidt@ur.de)

Further information about the project and its team is also available on the [Missbrauchsmuster website](https://missbrauchsmuster.de/).

### Licensing

Unless otherwise indicated, the project's documentation and other explicitly designated materials are made available under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

- **Documentation and guidelines:** CC BY 4.0, where the project holds the necessary rights.
- **Annotation schemes, figures, and derived results:** CC BY 4.0 where applicable, subject to the rights associated with the underlying material.
- **Source code:** Licensed separately under the MIT License, where applicable.
- **Third-party material and restricted data:** Excluded from the above licenses unless explicitly stated otherwise.

Please consult the relevant license file or resource-specific notice before reusing any material. The presence of a file in this repository does not, by itself, establish that the project has the right to redistribute its contents.

For details, see the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).

If you use material for research purposes in any publications please reference one of the papers below:

## Related publications

The following publications report on research conducted within or closely related to EpIEpA.

### Peer-reviewed publications and conference papers

- Hürten, M., Schmidt, T., Leimgruber, U. & Wolff, C. (2026). **Sexual Abuse in the Catholic Church: Annotation and Machine Learning of Hidden Patterns in Abuse Reports.** In *Digital Humanities Benelux 2026 Conference (DHBenelux 2026)*. Maastricht, Netherlands. https://doi.org/10.5281/zenodo.19663945

- Schmidt, T., & Hürten, M., Leimgruber, U. & Wolff, C. (2026). **Silenced in the Data: Epistemic Injustice as Challenge for the AI-Assisted Analysis of Abuse in the Catholic Church.** Long paper presented at the *Digital Humanities Conference 2026*, Daejeon, South Korea. https://doi.org/10.5281/zenodo.22149505

- Hürten, M., & Schmidt, T. (2026). **Epistemic Injustice and Ecclesial Discourse: A Digital Humanities Perspective on the Sexual Abuse of Women in the Catholic Church.** Poster presented at the *Digital Humanities Conference 2026*, Daejeon, South Korea. https://doi.org/10.5281/zenodo.22149826

### Further project contributions

- Hürten, M., & Schmidt, T. (2026). **From Epistemic Injustice to Epistemic Awareness: A Digital Humanities Approach to Research on Abuse against Women in the Catholic Church.** Lightning talk at *Theological Research, Teaching, and Infrastructure in the Context of Digitalization and AI*, Tübingen, Germany, February 13, 2026. http://dx.doi.org/10.15496/publikation-117857

For further talks, posters, and project updates, see the [official project page](https://missbrauchsmuster.de/forschen/projekte/forschungsprojekt-von-epistemic-injustice-zu-epistemic-awareness-prozessbasierte-methodenforschung-zu-missbrauch-an-erwachsenen-frauen-in-der-katholischen-kirche/).

---

*EpIEpA — From Epistemic Injustice to Epistemic Awareness*  
University of Regensburg · 2025–2028

