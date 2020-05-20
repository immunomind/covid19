[![Follow](https://img.shields.io/twitter/follow/immunomind.svg?style=social)](https://twitter.com/intent/follow?screen_name=immunomind)

# COVID19 dataset list
🦠 List of publicly available datasets with single-cell (scRNAseq) and immune repertoire (AIRR / RepSeq / immunosequencing) data of COVID-19 patients with SARS-CoV-2 infection. The repository is regularly updated with the community help and is managed by [ImmunoMind](https://immunomind.io) team.

:star: The project is open to any kind of contribution. If you want to add a new publicly available dataset, request or ask something please proceed to the [Contribution guide](contributing.md).

🧬 The T-cell / antibody immune repertoire data could be analyzed with [Immunarch](https://github.com/immunomind/immunarch). The scRNAseq data could be analyzed with the [scVI package](https://github.com/YosefLab/scVI) and [Seurat](https://github.com/satijalab/seurat).


<p align="center">
    <a href="#dataset-list">Dataset list</a>&nbsp;&nbsp;&nbsp;
    <a href="#datasets-in-details">Datasets in details</a>&nbsp;&nbsp;&nbsp;
    <a href="contributing.md">Contribution guide</a>&nbsp;&nbsp;&nbsp;
    <a href="https://twitter.com/immunomind">Twitter updates</a>&nbsp;&nbsp;&nbsp;
    </p>

# Dataset list
| Data public availability     | Data type   | Publication title                                                                                                                                      |
|:-----------------------------|:------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------|
| :heavy_check_mark: Available | AIRR        | <a name="0_short"></a>[B cell clonal expansion and convergent antibody responses to SARS-CoV-2](#0_long)                                               |
| :heavy_check_mark: Available | AIRR        | <a name="1_short"></a>[The landscape of lung bronchoalveolar immune cells in COVID-19 revealed by single-cell RNA sequencing](#1_long)                 |
| :heavy_check_mark: Available | scRNAseq    | <a name="2_short"></a>[Single-cell RNA expression profiling of ACE2, the receptor of SARS-CoV-2](#2_long)                                              |
| :question: Pending           | AIRR        | <a name="3_short"></a>[Immune cell profiling of COVID-19 patients in the recovery stage by single-cell sequencing](#3_long)                            |
| :question: Pending           | AIRR        | <a name="4_short"></a>[Microsoft and Adaptive Biotechnologies are studying how the human immune system reacts to the coronavirus: MSNBC](#4_long)      |
| :question: Pending           | AIRR        | <a name="5_short"></a>[Blood single cell immune profiling reveals the interferon-MAPK pathway mediated adaptive immune response for COVID-19](#5_long) |
| :question: Pending           | scRNAseq    | <a name="6_short"></a>[New Single-Cell Technologies Help Scientists Understand COVID-19 Disease Progression](#6_long)                                  |
| :question: Pending           | scRNAseq    | <a name="7_short"></a>[SARS‐CoV‐2 receptor ACE2 and TMPRSS2 are primarily expressed in bronchial transient secretory cells](#7_long)                   |

# Datasets in details
- <a name="0_long"></a>[:arrow_left: Back to table](#0_short)
- [B cell clonal expansion and convergent antibody responses to SARS-CoV-2](https://dx.doi.org/10.21203/rs.3.rs-27220/v1)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://dx.doi.org/10.21203/rs.3.rs-27220/v1
  - **Publication abstract\Press release:** During virus infection B cells are critical for the production of antibodies and protective immunity. Establishment of a diverse antibody repertoire occurs by rearrangement of germline DNA at the immunoglobulin heavy and light chain loci to encode the membrane-bound form of antibodies, the B cell antigen receptor. Little is known about the B cells and antigen receptors stimulated by the novel human coronavirus SARS-CoV-2. Here we show that the human B cell compartment in patients with diagnostically confirmed SARS-CoV-2 and clinical COVID-19 is rapidly altered with the early recruitment of B cells expressing a limited subset of V genes, and extensive activation of IgG and IgA subclasses without significant somatic mutation. We detect expansion of B cell clones as well as convergent antibodies with highly similar sequences across SARS-CoV-2 patients, highlighting stereotyped naïve responses to this virus. A shared convergent B cell clonotype in SARS-CoV-2 infected patients was previously seen in patients with SARS. These findings offer molecular insights into shared features of human B cell responses to SARS-CoV-2 and other zoonotic spillover coronaviruses.
  - **Dataset link:** https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA628125
  - **Sharing statement:** https://www.researchsquare.com/article/rs-27220/v1 
<br/>

- <a name="1_long"></a>[:arrow_left: Back to table](#1_short)
- [The landscape of lung bronchoalveolar immune cells in COVID-19 revealed by single-cell RNA sequencing](https://doi.org/10.1101/2020.02.23.20026690)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.02.23.20026690
  - **Publication abstract\Press release:** The novel coronavirus SARS-CoV-2, etiological agent of recently named Coronavirus infected disease (COVID-19) by WHO, has caused more than 2, 000 deaths worldwide since its emergency in Wuhan City, Hubei province, China, in December, 2019. The symptoms of COVID-19 varied from modest, mild to acute respiratory distress syndrome (ARDS), and the latter of which is generally associated with deregulated immune cytokine production; however, we currently know little as to the interplay between the extent of clinical symptoms and the compositions of lung immune microenvironment. Here, we comprehensively characterized the lung immune microenvironment with the bronchoalveolar lavage fluid (BALF) from 3 severe and 3 mild COVID-19 patients and 8 previously reported healthy lung controls through single-cell RNA sequence (scRNA-seq) combined with TCR-seq. Our data shows that monocyte-derived FCN1+ macrophages, whereas notFABP4+ alveolar macrophages that represent a predominant macrophage subset in BALF from patients with mild diseases, overwhelm in the severely damaged lungs from patients with ARDS. These cells are highly inflammatory and enormous chemokine producers implicated in cytokine storm. Furthermore, the formation of tissue resident, highly expanded clonal CD8+ T cells in the lung microenvironment of mild symptom patients suggests a robust adaptive immune response connected to a better control of COVID-19. This study first reported the cellular atlas of lung bronchoalveolar immune microenvironment in COVID-19 patients at the single-cell resolution, and unveiled the potential immune mechanisms underlying disease progression and protection in COVID-19.
  - **Dataset link:** https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA608742
  - **Sharing statement:** https://www.medrxiv.org/node/72689.external-links.html
<br/>

- <a name="2_long"></a>[:arrow_left: Back to table](#2_short)
- [Single-cell RNA expression profiling of ACE2, the receptor of SARS-CoV-2](https://doi.org/10.1101/2020.01.26.919985)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** scRNAseq
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.01.26.919985
  - **Publication abstract\Press release:** A novel coronavirus SARS-CoV-2 was identified in Wuhan, Hubei Province, China in December of 2019. According to WHO report, this new coronavirus has resulted in 76,392 confirmed infections and 2,348 deaths in China by 22 February, 2020, with additional patients being identified in a rapidly growing number internationally. SARS-CoV-2 was reported to share the same receptor, Angiotensin-converting enzyme 2 (ACE2), with SARS-CoV. Here based on the public database and the state-of-the-art single-cell RNA-Seq technique, we analyzed the ACE2 RNA expression profile in the normal human lungs. The result indicates that the ACE2 virus receptor expression is concentrated in a small population of type II alveolar cells (AT2). Surprisingly, we found that this population of ACE2-expressing AT2 also highly expressed many other genes that positively regulating viral entry, reproduction and transmission. This study provides a biological background for the epidemic investigation of the COVID-19, and could be informative for future anti-ACE2 therapeutic strategy development.
  - **Dataset link:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE122960
  - **Sharing statement:** Used public data
<br/>

- <a name="3_long"></a>[:arrow_left: Back to table](#3_short)
- [Immune cell profiling of COVID-19 patients in the recovery stage by single-cell sequencing](https://doi.org/10.1038/s41421-020-0168-9)
  - **Data public availability:** :question: Pending
  - **Data type:** AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1038/s41421-020-0168-9
  - **Publication abstract\Press release:** COVID-19, caused by SARS-CoV-2, has recently affected over 1,200,000 people and killed more than 60,000. The key immune cell subsets change and their states during the course of COVID-19 remain unclear. We sought to comprehensively characterize the transcriptional changes in peripheral blood mononuclear cells during the recovery stage of COVID-19 by single-cell RNA sequencing technique. It was found that T cells decreased remarkably, whereas monocytes increased in patients in the early recovery stage (ERS) of COVID-19. There was an increased ratio of classical CD14++ monocytes with high inflammatory gene expression as well as a greater abundance of CD14++IL1β+ monocytes in the ERS. CD4+ T cells and CD8+ T cells decreased significantly and expressed high levels of inflammatory genes in the ERS. Among the B cells, the plasma cells increased remarkably, whereas the naïve B cells decreased. Several novel B cell-receptor (BCR) changes were identified, such as IGHV3-23 and IGHV3-7, and isotypes (IGHV3-15, IGHV3-30, and IGKV3-11) previously used for virus vaccine development were confirmed. The strongest pairing frequencies, IGHV3-23-IGHJ4, indicated a monoclonal state associated with SARS-CoV-2 specificity, which had not been reported yet. Furthermore, integrated analysis predicted that IL-1β and M-CSF may be novel candidate target genes for inflammatory storm and that TNFSF13, IL-18, IL-2, and IL-4 may be beneficial for the recovery of COVID-19 patients. Our study provides the first evidence of an inflammatory immune signature in the ERS, suggesting COVID-19 patients are still vulnerable after hospital discharge. Identification of novel BCR signaling may lead to the development of vaccines and antibodies for the treatment of COVID-19.
  - **Dataset link:** Pending
  - **Sharing statement:** https://www.nature.com/articles/s41421-020-0168-9#data-availability
<br/>

- <a name="4_long"></a>[:arrow_left: Back to table](#4_short)
- [Microsoft and Adaptive Biotechnologies are studying how the human immune system reacts to the coronavirus: MSNBC](https://www.cnbc.com/2020/03/20/microsoft-adaptive-studying-coronavirus-immune-system-reaction.html)
  - **Data public availability:** :question: Pending
  - **Data type:** AIRR
  - **Source type:** Website
  - **Publication DOI:** Not available
  - **Publication abstract\Press release:** Microsoft and Adaptive Biotechnologies are spearheading an effort to understand how the human immune system responds to the virus, and why some people become so critically ill while others are asymptomatic.
The companies are collecting anonymous blood samples from people who have been diagnosed with the disease and have subsequently recovered.
The research findings will be shared via an open access data-set so others can leverage it so develop better treatments for Covid-19.
  - **Dataset link:** Pending
  - **Sharing statement:** https://www.cnbc.com/2020/03/20/microsoft-adaptive-studying-coronavirus-immune-system-reaction.html
<br/>

- <a name="5_long"></a>[:arrow_left: Back to table](#5_short)
- [Blood single cell immune profiling reveals the interferon-MAPK pathway mediated adaptive immune response for COVID-19](https://doi.org/10.1101/2020.03.15.20033472)
  - **Data public availability:** :question: Pending
  - **Data type:** AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.03.15.20033472
  - **Publication abstract\Press release:** The coronavirus disease 2019 (COVID-19) outbreak is an ongoing global health emergence, but the pathogenesis remains unclear. We revealed blood cell immune response profiles using 5' mRNA, TCR and BCR V(D)J transcriptome analysis with single-cell resolution. Data from 134,620 PBMCs and 83,387 TCR and 12,601 BCR clones was obtained, and 56 blood cell subtypes and 23 new cell marker genes were identified from 16 participants. The number of specific subtypes of immune cells changed significantly when compared patients with controls. Activation of the interferon-MAPK pathway is the major defense mechanism, but MAPK transcription signaling is inhibited in cured patients. TCR and BCR V(D)J recombination is highly diverse in generating different antibodies against SARS-CoV-2. Therefore, the interferon-MAPK pathway and TCR- and BCR-produced antibodies play important roles in the COVID-19 immune response. Immune deficiency or immune over-response may result in the condition of patients with COVID-19 becoming critical or severe.
  - **Dataset link:** Pending
  - **Sharing statement:** https://www.medrxiv.org/node/73721.external-links.html
<br/>

- <a name="6_long"></a>[:arrow_left: Back to table](#6_short)
- [New Single-Cell Technologies Help Scientists Understand COVID-19 Disease Progression](https://chanzuckerberg.com/newsroom/)
  - **Data public availability:** :question: Pending
  - **Data type:** scRNAseq
  - **Source type:** Website
  - **Publication DOI:** Not available
  - **Publication abstract\Press release:** Today, the Chan Zuckerberg Initiative (CZI) announced $750,000 in funding to support five distinct projects studying how COVID-19 progresses in patients at the level of individual cells and tissues. This work will generate some of the first single-cell biology datasets from donors infected by SARS-CoV2 and provide critical insights into how the virus infects humans, which cell types are involved, and how the disease progresses.
  - **Dataset link:** Pending
  - **Sharing statement:** https://chanzuckerberg.com/newsroom/
<br/>

- <a name="7_long"></a>[:arrow_left: Back to table](#7_short)
- [SARS‐CoV‐2 receptor ACE2 and TMPRSS2 are primarily expressed in bronchial transient secretory cells](https://doi.org/10.15252/embj.20105114)
  - **Data public availability:** :question: Pending
  - **Data type:** scRNAseq
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.15252/embj.20105114
  - **Publication abstract\Press release:** The SARS‐CoV‐2 pandemic affecting the human respiratory system severely challenges public health and urgently demands for increasing our understanding of COVID‐19 pathogenesis, especially host factors facilitating virus infection and replication. SARS‐CoV‐2 was reported to enter cells via binding to ACE2, followed by its priming by TMPRSS2. Here, we investigate ACE2 and TMPRSS2 expression levels and their distribution across cell types in lung tissue (twelve donors, 39,778 cells) and in cells derived from subsegmental bronchial branches (four donors, 17,521 cells) by single nuclei and single cell RNA sequencing, respectively. While TMPRSS2 is strongly expressed in both tissues, in the subsegmental bronchial branches ACE2 is predominantly expressed in a transient secretory cell type. Interestingly, these transiently differentiating cells show an enrichment for pathways related to RHO GTPase function and viral processes suggesting increased vulnerability for SARS‐CoV‐2 infection. Our data provide a rich resource for future investigations of COVID‐19 infection and pathogenesis.
  - **Dataset link:** Pending
  - **Sharing statement:** https://www.embopress.org/doi/10.15252/embj.20105114#embj20105114-sec-0019-title
<br/>



# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

