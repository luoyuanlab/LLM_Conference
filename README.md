# LLM_Conference
LLM for conference organization
# AMIA 2024 Informatics Summit Conference Organization with LLMs
This repository contains code and data used for organizing the **American Medical Informatics Association (AMIA) 2024 Informatics Summit**, leveraging Large Language Models (LLMs) to enhance the efficiency and coherence of conference planning.

## Overview

We utilized LLMs to assist with the following key conference organization tasks:

- **Reviewer Assignment:** Algorithmic matching of reviewers to submissions based on keyword overlaps and conflict of interest checks.
- **Session Grouping:** Grouping accepted presentations into coherent thematic sessions.
- **Session Naming:** Generating concise and informative session titles.
- **Presentation Summarization:** Producing one-sentence summaries for each presentation to improve attendee navigation.

All data used in this project, including presentation titles, abstracts, and keywords, are publicly available and do **not** contain any protected health information (PHI) or personally identifiable information (PII).

## Repository Structure

The repository contains the following files:

### Jupyter Notebooks
- `PCMatch_AMIA_IS24.ipynb` - Algorithmic matching of reviewers to submissions (code wtih LLM assistance).
- `paperCluster_AMIA_IS24.ipynb` - Groups accepted presentations into thematic sessions using LLM-based embeddings and clustering.
- `posterThemes_AMIA_IS24.ipynb` - Organizes poster presentations by themes.
- `paperSummarization_AMIA_IS24.ipynb` - Generates concise one-sentence summaries for accepted presentations.
- `sessionName_AMIA_IS24.ipynb` - Generates informative session names based on presentation content.

### Data Files

- `accepted_paper_podium_AMIA_IS24.csv` - List of accepted papers (titles, abstracts, and keywords).
- `accepted_poster_AMIA_IS24.csv` - List of accepted posters (titles, abstracts, and keywords).


## Ethical Considerations

- All data used in this project are publicly available and contain **no PHI or PII**.
- LLMs were used responsibly to complement human oversight and ensure the quality of results.

## Acknowledgments

This project was conducted by the AMIA 2024 Informatics Summit Scientific Program Committee Chair and Vice Chairs and with the support and collaboration of AMIA leadership and staff.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or contributions, please contact:

- **Yuan Luo** (Conference Chair for AMIA 2024 Informatics Summit) - [Email](mailto:yuan.luo@northwestern.edu)

## Citation

If you use this work, please cite:

Luo, Yuan, Yikuan Li, Omolola Ogunyemi, Eileen Koski, Blanca E. Himes. "Leveraging Large Language Models for Academic Conference Organization." To appear.

---

We hope this repository serves as a valuable resource for future academic conference planning using AI-driven methods!

