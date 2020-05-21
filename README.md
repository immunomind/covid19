[![Follow](https://img.shields.io/twitter/follow/immunomind.svg?style=social)](https://twitter.com/intent/follow?screen_name=immunomind)

# COVID19 dataset list
🦠 To accelerate the COVID-19 research and vaccine development we collected a list of publicly available datasets with single-cell (scRNAseq) and immune repertoire (AIRR / RepSeq / immunosequencing) data. The data comes from confirmed COVID-19 patients or from human cell lines infected with SARS-CoV-2. The repository is regularly updated with community’s help and is managed by the [ImmunoMind](https://immunomind.io) team.

:star: The contribution to the project is warmly welcome. To add a new publicly available dataset, request or ask something please create a new issue according to our [Contribution guide](contributing.md).

🧬 We recommend to use [Immunarch](https://github.com/immunomind/immunarch) to analyse the T-cell / antibody immune repertoire data or the [scVI package](https://github.com/YosefLab/scVI) and [Seurat](https://github.com/satijalab/seurat) to analyse the scRNAseq gene expression data.

<p align="center">
    <a href="#dataset-list">Dataset list</a>&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="#datasets-in-details">Datasets in details</a>&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="contributing.md">Contribution guide</a>&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://twitter.com/immunomind">Twitter updates</a>&nbsp;&nbsp;&nbsp;&nbsp;
    </p>

# Dataset list
| Data public availability     | Data type       | Publication title                                                                                                                                                                                                     |
|:-----------------------------|:----------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| :heavy_check_mark: Available | AIRR            | <a name="0_short"></a>[:arrow_right: B cell clonal expansion and convergent antibody responses to SARS-CoV-2](#0_long)                                                                                                |
| :heavy_check_mark: Available | AIRR            | <a name="1_short"></a>[:arrow_right: The landscape of lung bronchoalveolar immune cells in COVID-19 revealed by single-cell RNA sequencing](#1_long)                                                                  |
| :heavy_check_mark: Available | scRNAseq        | <a name="2_short"></a>[:arrow_right: Single-cell RNA expression profiling of ACE2, the receptor of SARS-CoV-2](#2_long)                                                                                               |
| :question: Pending           | scRNAseq + AIRR | <a name="3_short"></a>[:arrow_right: Immune cell profiling of COVID-19 patients in the recovery stage by single-cell sequencing](#3_long)                                                                             |
| :question: Pending           | AIRR            | <a name="4_short"></a>[:arrow_right: Microsoft and Adaptive Biotechnologies are studying how the human immune system reacts to the coronavirus: MSNBC](#4_long)                                                       |
| :question: Pending           | scRNAseq + AIRR | <a name="5_short"></a>[:arrow_right: Blood single cell immune profiling reveals the interferon-MAPK pathway mediated adaptive immune response for COVID-19](#5_long)                                                  |
| :question: Pending           | scRNAseq        | <a name="6_short"></a>[:arrow_right: New Single-Cell Technologies Help Scientists Understand COVID-19 Disease Progression](#6_long)                                                                                   |
| :question: Pending           | scRNAseq        | <a name="7_short"></a>[:arrow_right: SARS‐CoV‐2 receptor ACE2 and TMPRSS2 are primarily expressed in bronchial transient secretory cells](#7_long)                                                                    |
| :heavy_check_mark: Available | AIRR            | <a name="8_short"></a>[:arrow_right: Longitudinal high-throughput TCR repertoire profiling reveals the dynamics of T cell memory formation after mild COVID-19 infection](#8_long)                                    |
| :heavy_check_mark: Available | scRNAseq + AIRR | <a name="9_short"></a>[:arrow_right: Potent neutralizing antibodies against SARS-CoV-2 identified by high-throughput single-cell sequencing of convalescent patients’ B cells](#9_long)                               |
| :question: Pending           | scRNAseq        | <a name="10_short"></a>[:arrow_right: Single-cell longitudinal analysis of SARS-CoV-2 infection in human bronchial epithelial cells](#10_long)                                                                        |
| Upon request                 | scRNAseq + AIRR | <a name="11_short"></a>[:arrow_right: Tocilizumab treatment in severe COVID-19 patients attenuates the inflammatory storm incited by monocyte centric immune interactions revealed by single-cell analysis](#11_long) |
| :heavy_check_mark: Available | scRNAseq + AIRR | <a name="12_short"></a>[:arrow_right: A molecular cell atlas of the human lung from single cell RNA sequencing](#12_long)                                                                                             |
| :heavy_check_mark: Available | scRNAseq        | <a name="13_short"></a>[:arrow_right: Bulk and single-cell gene expression profiling of SARS-CoV-2 infected human cell lines identifies molecular targets for therapeutic intervention](#13_long)                     |
| :heavy_check_mark: Available | AIRR            | <a name="14_short"></a>[:arrow_right: Immunologic perturbations in severe COVID-19/SARS-CoV-2 infection](#14_long)                                                                                                    |
| :heavy_check_mark: Available | scRNAseq        | <a name="15_short"></a>[:arrow_right: Identification of Candidate COVID-19 Therapeutics using hPSC-derived Lung Organoids](#15_long)                                                                                  |

# Datasets in details
- <a name="0_long"></a>[:arrow_left: Back to the list](#0_short)
- [B cell clonal expansion and convergent antibody responses to SARS-CoV-2](https://dx.doi.org/10.21203/rs.3.rs-27220/v1)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://dx.doi.org/10.21203/rs.3.rs-27220/v1
  - **Publication abstract\Press release:** During virus infection B cells are critical for the production of antibodies and protective immunity. Establishment of a diverse antibody repertoire occurs by rearrangement of germline DNA at the immunoglobulin heavy and light chain loci to encode the membrane-bound form of antibodies, the B cell antigen receptor. Little is known about the B cells and antigen receptors stimulated by the novel human coronavirus SARS-CoV-2. Here we show that the human B cell compartment in patients with diagnostically confirmed SARS-CoV-2 and clinical COVID-19 is rapidly altered with the early recruitment of B cells expressing a limited subset of V genes, and extensive activation of IgG and IgA subclasses without significant somatic mutation. We detect expansion of B cell clones as well as convergent antibodies with highly similar sequences across SARS-CoV-2 patients, highlighting stereotyped naïve responses to this virus. A shared convergent B cell clonotype in SARS-CoV-2 infected patients was previously seen in patients with SARS. These findings offer molecular insights into shared features of human B cell responses to SARS-CoV-2 and other zoonotic spillover coronaviruses.
  - **Dataset link:** https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA628125
  - **Sharing statement:** https://www.researchsquare.com/article/rs-27220/v1 
<br/>

- <a name="1_long"></a>[:arrow_left: Back to the list](#1_short)
- [The landscape of lung bronchoalveolar immune cells in COVID-19 revealed by single-cell RNA sequencing](https://doi.org/10.1101/2020.02.23.20026690)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.02.23.20026690
  - **Publication abstract\Press release:** The novel coronavirus SARS-CoV-2, etiological agent of recently named Coronavirus infected disease (COVID-19) by WHO, has caused more than 2, 000 deaths worldwide since its emergency in Wuhan City, Hubei province, China, in December, 2019. The symptoms of COVID-19 varied from modest, mild to acute respiratory distress syndrome (ARDS), and the latter of which is generally associated with deregulated immune cytokine production; however, we currently know little as to the interplay between the extent of clinical symptoms and the compositions of lung immune microenvironment. Here, we comprehensively characterized the lung immune microenvironment with the bronchoalveolar lavage fluid (BALF) from 3 severe and 3 mild COVID-19 patients and 8 previously reported healthy lung controls through single-cell RNA sequence (scRNA-seq) combined with TCR-seq. Our data shows that monocyte-derived FCN1+ macrophages, whereas notFABP4+ alveolar macrophages that represent a predominant macrophage subset in BALF from patients with mild diseases, overwhelm in the severely damaged lungs from patients with ARDS. These cells are highly inflammatory and enormous chemokine producers implicated in cytokine storm. Furthermore, the formation of tissue resident, highly expanded clonal CD8+ T cells in the lung microenvironment of mild symptom patients suggests a robust adaptive immune response connected to a better control of COVID-19. This study first reported the cellular atlas of lung bronchoalveolar immune microenvironment in COVID-19 patients at the single-cell resolution, and unveiled the potential immune mechanisms underlying disease progression and protection in COVID-19.
  - **Dataset link:** https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA608742
  - **Sharing statement:** https://www.medrxiv.org/node/72689.external-links.html
<br/>

- <a name="2_long"></a>[:arrow_left: Back to the list](#2_short)
- [Single-cell RNA expression profiling of ACE2, the receptor of SARS-CoV-2](https://doi.org/10.1101/2020.01.26.919985)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** scRNAseq
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.01.26.919985
  - **Publication abstract\Press release:** A novel coronavirus SARS-CoV-2 was identified in Wuhan, Hubei Province, China in December of 2019. According to WHO report, this new coronavirus has resulted in 76,392 confirmed infections and 2,348 deaths in China by 22 February, 2020, with additional patients being identified in a rapidly growing number internationally. SARS-CoV-2 was reported to share the same receptor, Angiotensin-converting enzyme 2 (ACE2), with SARS-CoV. Here based on the public database and the state-of-the-art single-cell RNA-Seq technique, we analyzed the ACE2 RNA expression profile in the normal human lungs. The result indicates that the ACE2 virus receptor expression is concentrated in a small population of type II alveolar cells (AT2). Surprisingly, we found that this population of ACE2-expressing AT2 also highly expressed many other genes that positively regulating viral entry, reproduction and transmission. This study provides a biological background for the epidemic investigation of the COVID-19, and could be informative for future anti-ACE2 therapeutic strategy development.
  - **Dataset link:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE122960
  - **Sharing statement:** Used public data
<br/>

- <a name="3_long"></a>[:arrow_left: Back to the list](#3_short)
- [Immune cell profiling of COVID-19 patients in the recovery stage by single-cell sequencing](https://doi.org/10.1038/s41421-020-0168-9)
  - **Data public availability:** :question: Pending
  - **Data type:** scRNAseq + AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1038/s41421-020-0168-9
  - **Publication abstract\Press release:** COVID-19, caused by SARS-CoV-2, has recently affected over 1,200,000 people and killed more than 60,000. The key immune cell subsets change and their states during the course of COVID-19 remain unclear. We sought to comprehensively characterize the transcriptional changes in peripheral blood mononuclear cells during the recovery stage of COVID-19 by single-cell RNA sequencing technique. It was found that T cells decreased remarkably, whereas monocytes increased in patients in the early recovery stage (ERS) of COVID-19. There was an increased ratio of classical CD14++ monocytes with high inflammatory gene expression as well as a greater abundance of CD14++IL1β+ monocytes in the ERS. CD4+ T cells and CD8+ T cells decreased significantly and expressed high levels of inflammatory genes in the ERS. Among the B cells, the plasma cells increased remarkably, whereas the naïve B cells decreased. Several novel B cell-receptor (BCR) changes were identified, such as IGHV3-23 and IGHV3-7, and isotypes (IGHV3-15, IGHV3-30, and IGKV3-11) previously used for virus vaccine development were confirmed. The strongest pairing frequencies, IGHV3-23-IGHJ4, indicated a monoclonal state associated with SARS-CoV-2 specificity, which had not been reported yet. Furthermore, integrated analysis predicted that IL-1β and M-CSF may be novel candidate target genes for inflammatory storm and that TNFSF13, IL-18, IL-2, and IL-4 may be beneficial for the recovery of COVID-19 patients. Our study provides the first evidence of an inflammatory immune signature in the ERS, suggesting COVID-19 patients are still vulnerable after hospital discharge. Identification of novel BCR signaling may lead to the development of vaccines and antibodies for the treatment of COVID-19.
  - **Dataset link:** Pending
  - **Sharing statement:** https://www.nature.com/articles/s41421-020-0168-9#data-availability
<br/>

- <a name="4_long"></a>[:arrow_left: Back to the list](#4_short)
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

- <a name="5_long"></a>[:arrow_left: Back to the list](#5_short)
- [Blood single cell immune profiling reveals the interferon-MAPK pathway mediated adaptive immune response for COVID-19](https://doi.org/10.1101/2020.03.15.20033472)
  - **Data public availability:** :question: Pending
  - **Data type:** scRNAseq + AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.03.15.20033472
  - **Publication abstract\Press release:** The coronavirus disease 2019 (COVID-19) outbreak is an ongoing global health emergence, but the pathogenesis remains unclear. We revealed blood cell immune response profiles using 5' mRNA, TCR and BCR V(D)J transcriptome analysis with single-cell resolution. Data from 134,620 PBMCs and 83,387 TCR and 12,601 BCR clones was obtained, and 56 blood cell subtypes and 23 new cell marker genes were identified from 16 participants. The number of specific subtypes of immune cells changed significantly when compared patients with controls. Activation of the interferon-MAPK pathway is the major defense mechanism, but MAPK transcription signaling is inhibited in cured patients. TCR and BCR V(D)J recombination is highly diverse in generating different antibodies against SARS-CoV-2. Therefore, the interferon-MAPK pathway and TCR- and BCR-produced antibodies play important roles in the COVID-19 immune response. Immune deficiency or immune over-response may result in the condition of patients with COVID-19 becoming critical or severe.
  - **Dataset link:** Pending
  - **Sharing statement:** https://www.medrxiv.org/node/73721.external-links.html
<br/>

- <a name="6_long"></a>[:arrow_left: Back to the list](#6_short)
- [New Single-Cell Technologies Help Scientists Understand COVID-19 Disease Progression](https://chanzuckerberg.com/newsroom/)
  - **Data public availability:** :question: Pending
  - **Data type:** scRNAseq
  - **Source type:** Website
  - **Publication DOI:** Not available
  - **Publication abstract\Press release:** Today, the Chan Zuckerberg Initiative (CZI) announced $750,000 in funding to support five distinct projects studying how COVID-19 progresses in patients at the level of individual cells and tissues. This work will generate some of the first single-cell biology datasets from donors infected by SARS-CoV2 and provide critical insights into how the virus infects humans, which cell types are involved, and how the disease progresses.
  - **Dataset link:** Pending
  - **Sharing statement:** https://chanzuckerberg.com/newsroom/
<br/>

- <a name="7_long"></a>[:arrow_left: Back to the list](#7_short)
- [SARS‐CoV‐2 receptor ACE2 and TMPRSS2 are primarily expressed in bronchial transient secretory cells](https://doi.org/10.15252/embj.20105114)
  - **Data public availability:** :question: Pending
  - **Data type:** scRNAseq
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.15252/embj.20105114
  - **Publication abstract\Press release:** The SARS‐CoV‐2 pandemic affecting the human respiratory system severely challenges public health and urgently demands for increasing our understanding of COVID‐19 pathogenesis, especially host factors facilitating virus infection and replication. SARS‐CoV‐2 was reported to enter cells via binding to ACE2, followed by its priming by TMPRSS2. Here, we investigate ACE2 and TMPRSS2 expression levels and their distribution across cell types in lung tissue (twelve donors, 39,778 cells) and in cells derived from subsegmental bronchial branches (four donors, 17,521 cells) by single nuclei and single cell RNA sequencing, respectively. While TMPRSS2 is strongly expressed in both tissues, in the subsegmental bronchial branches ACE2 is predominantly expressed in a transient secretory cell type. Interestingly, these transiently differentiating cells show an enrichment for pathways related to RHO GTPase function and viral processes suggesting increased vulnerability for SARS‐CoV‐2 infection. Our data provide a rich resource for future investigations of COVID‐19 infection and pathogenesis.
  - **Dataset link:** Pending
  - **Sharing statement:** https://www.embopress.org/doi/10.15252/embj.20105114#embj20105114-sec-0019-title
<br/>

- <a name="8_long"></a>[:arrow_left: Back to the list](#8_short)
- [Longitudinal high-throughput TCR repertoire profiling reveals the dynamics of T cell memory formation after mild COVID-19 infection](https://doi.org/10.1101/2020.05.18.100545)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.05.18.100545
  - **Publication abstract\Press release:** COVID-19 is a global pandemic caused by the SARS-CoV-2 coronavirus. T cell response is a critical part of both individual and herd immunity to SARS-CoV-2 and the efficacy of developed vaccines. However neither the dynamics and cross-reactivity of the SARS-CoV-2-specific T cell response nor the diversity of resulting immune memory are well understood. In this study we use longitudinal high-throughput T cell receptor sequencing to track changes in the T cell repertoire following two mild cases of COVID-19 infection. In both donors we identified SARS-CoV-2-responding CD4+ and CD8+ T cell clones. We describe characteristic motifs in TCR sequences of COVID-19-reactive clones, suggesting the existence of immunodominant epitopes. We show that in both donors the majority of infection-reactive clonotypes acquire memory phenotypes. Certain CD4+ clones were detected in the memory fraction at the pre-infection timepoint, suggesting participation of pre-existing cross-reactive memory T cells in the immune response to SARS-CoV-2.
  - **Dataset link:** PRJNA633317
  - **Sharing statement:** Raw sequencing data are deposited to the Short ReadArchive  (SRA)  accession:   PRJNA633317.ProcessedTCRalpha  and  TCRbeta  repertoire  datasets,  resultingrepertoires of SARS-CoV-2-reactive clones, and raw datapreprocessing instructions can be accessed from:https://github.com/pogorely/Minervina_COVID.
<br/>

- <a name="9_long"></a>[:arrow_left: Back to the list](#9_short)
- [Potent neutralizing antibodies against SARS-CoV-2 identified by high-throughput single-cell sequencing of convalescent patients’ B cells](https://doi.org/10.1016/j.cell.2020.05.025)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** scRNAseq + AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1016/j.cell.2020.05.025
  - **Publication abstract\Press release:** The COVID-19 pandemic urgently needs therapeutic and prophylactic interventions. Here we report the rapid identification of SARS-CoV-2 neutralizing antibodies by high-throughput single-cell RNA and VDJ sequencing of antigen-enriched B cells from 60 convalescent patients. From 8,558 antigen-binding IgG1+ clonotypes, 14 potent neutralizing antibodies were identified with the most potent one, BD-368-2, exhibiting an IC50 of 1.2 ng/mL and 15 ng/mL against pseudotyped and authentic SARS-CoV-2, respectively. BD-368-2 also displayed strong therapeutic and prophylactic efficacy in SARS-CoV-2-infected hACE2-transgenic mice. Additionally, the 3.8Å Cryo-EM structure of a neutralizing antibody in complex with the spike-ectodomain trimer revealed the antibody’s epitope overlaps with the ACE2 binding site. Moreover, we demonstrated that SARS-CoV-2 neutralizing antibodies could be directly selected based on similarities of their predicted CDR3H structures to those of SARS-CoV neutralizing antibodies. Altogether, we showed that human neutralizing antibodies could be efficiently discovered by high-throughput single B-cell sequencing in response to pandemic infectious diseases.
  - **Dataset link:** EGAS00001004412
  - **Sharing statement:** Human antibody sequences are available on the European Genome-Phenome Archive (EGAS00001004412) upon publication in press. Material/Data Transfer Agreements, which allow the use of the antibody sequences for non-commercial purposes but not their disclosure to third parties, are needed to obtain the sequences by contacting the Data Access Committee.
<br/>

- <a name="10_long"></a>[:arrow_left: Back to the list](#10_short)
- [Single-cell longitudinal analysis of SARS-CoV-2 infection in human bronchial epithelial cells](https://doi.org/10.1101/2020.05.06.081695)
  - **Data public availability:** :question: Pending
  - **Data type:** scRNAseq
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.05.06.081695
  - **Publication abstract\Press release:** SARS-CoV-2, the causative agent of COVID-19, has resulted in more than 3,000,000 infections and 200,000 deaths. There are currently no approved drugs or vaccines for the treatment or prevention of COVID-19. Enhanced understanding of SARS-CoV-2 infection and pathogenesis is critical for the development of therapeutics. To reveal insight into viral replication, cell tropism, and host-viral interactions of SARS-CoV-2 we performed single-cell RNA sequencing of experimentally infected human bronchial epithelial cells (HBECs) in air-liquid interface cultures over a time-course. This revealed novel polyadenylated viral transcripts and highlighted ciliated cells as the major target of infection, which we confirmed by electron microscopy. Over the course of infection, cell tropism of SARS-CoV-2 expands to other epithelial cell types including basal and club cells. Infection induces cell intrinsic expression of type I and type III IFNs and IL6 but not IL1. This results in expression of interferon stimulated genes in both infected and bystander cells. Here, we have conducted an in-depth analysis of SARS-CoV-2 infection in HBECs and provide a detailed characterization of genes, cell types, and cell state changes associated with the infection.
  - **Dataset link:** Pending
  - **Sharing statement:** The scRNA-seq data will be made publicly available around two weeks after pre-print submission, to allow time for finalizing the manuscript. The data will be deposited in the NCBI Geo database.
<br/>

- <a name="11_long"></a>[:arrow_left: Back to the list](#11_short)
- [Tocilizumab treatment in severe COVID-19 patients attenuates the inflammatory storm incited by monocyte centric immune interactions revealed by single-cell analysis](https://doi.org/10.1101/2020.04.08.029769)
  - **Data public availability:** Upon request
  - **Data type:** scRNAseq + AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.04.08.029769
  - **Publication abstract\Press release:** Coronavirus disease 2019 (COVID-19)has caused more than40,000 deaths 42worldwide1.Approximately 14% of patients with COVID-19 experienced severe 43disease and 5% were critically ill2. Studies have shown that dysregulation of the 44COVID-19 patients’ immune system may lead to inflammatory stormand causesevere 45illness and even death3,4. Tocilizumab treatmenttargeting interleukin 6 receptor has 46shown inspiringclinical results of severe COVID-19 patients5.However,the immune 47network withTocilizumabtreatmentat single cell resolutionhas not been uncovered. 48Here, we profiled the single-cell transcriptomes of 13,289peripheral blood 49mononuclear cellsisolated at three longitudinalstages fromtwosevereCOVID-19 50patientstreated with Tocilizumab.Weidentifiedasevere stage-specific monocyte 51subpopulationand these cells centricimmune cell interaction network connected by the52inflammatory cytokines and their receptors.Theover-activated inflammatory immune53responsewasattenuatedafter Tocilizumab treatment, yet immune cells including 54plasma B cells and CD8+T cells still exhibited anintensehumoral and cell-mediated55anti-virus immune responsein recovered COVID-19 patients. These results provided56criticalinsights into the immunopathogenesisof severe COVID-19 and revealed 57fundamentalsof effectiveness inTocilizumab treatment.
  - **Dataset link:** Upon request
  - **Sharing statement:** We are uploading the scRNA-seq data of PBMCs from the 2 severe COVID-19 patients to the Genome Sequence Archive at BIG Data Center and the accession number will be available upon request.
<br/>

- <a name="12_long"></a>[:arrow_left: Back to the list](#12_short)
- [A molecular cell atlas of the human lung from single cell RNA sequencing](https://doi.org/10.1101/742320)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** scRNAseq + AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/742320
  - **Publication abstract\Press release:** Although single cell RNA sequencing studies have begun providing compendia of cell expression profiles, it has proven more difficult to systematically identify and localize all molecular cell types in individual organs to create a full molecular cell atlas. Here we describe droplet- and plate-based single cell RNA sequencing applied to ∼75,000 human lung and blood cells, combined with a multi-pronged cell annotation approach, which have allowed us to define the gene expression profiles and anatomical locations of 58 cell populations in the human lung, including 41 of 45 previously known cell types or subtypes and 14 new ones. This comprehensive molecular atlas elucidates the biochemical functions of lung cell types and the cell-selective transcription factors and optimal markers for making and monitoring them; defines the cell targets of circulating hormones and predicts local signaling interactions including sources and targets of chemokines in immune cell trafficking and expression changes on lung homing; and identifies the cell types directly affected by lung disease genes and respiratory viruses. Comparison to mouse identified 17 molecular types that appear to have been gained or lost during lung evolution and others whose expression profiles have been substantially altered, revealing extensive plasticity of cell types and cell-type-specific gene expression during organ evolution including expression switches between cell types. This atlas provides the molecular foundation for investigating how lung cell identities, functions, and interactions are achieved in development and tissue engineering and altered in disease and evolution.
  - **Dataset link:** syn21041850
  - **Sharing statement:** Counts/UMI tables, cellular metadata, Seurat objects, and scanpy objects are available on Synapse (accession syn21041850). The data can be explored in a browser using cellxgene at https://hlca.ds.czbiohub.org/. Code for demultiplexing counts/UMI tables, clustering, annotation, and other downstream analyses are available on GitHub (https://github.com/krasnowlab/HLCA). Human sequencing data will be available by data access agreement on the European Genome-phenome Archive (EGA) upon publication of this manuscript. Mouse sequencing data will be available on the National Institute of Health’s Sequence Read Archive (SRA) also upon publication of this manuscript.
<br/>

- <a name="13_long"></a>[:arrow_left: Back to the list](#13_short)
- [Bulk and single-cell gene expression profiling of SARS-CoV-2 infected human cell lines identifies molecular targets for therapeutic intervention](https://doi.org/10.1101/2020.05.05.079194)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** scRNAseq
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.05.05.079194
  - **Publication abstract\Press release:** The coronavirus disease 2019 (COVID-19) pandemic, caused by the novel severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2), is an ongoing global health threat with more than two million infected people since its emergence in late 2019. Detailed knowledge of the molecular biology of the infection is indispensable for understanding of the viral replication, host responses, and disease progression. We provide gene expression profiles of SARS-CoV and SARS-CoV-2 infections in three human cell lines (H1299, Caco-2 and Calu-3 cells), using bulk and single-cell transcriptomics. Small RNA profiling showed strong expression of the immunity and inflammation-associated microRNA miRNA-155 upon infection with both viruses. SARS-CoV-2 elicited approximately two-fold higher stimulation of the interferon response compared to SARS-CoV in the permissive human epithelial cell line Calu-3, and induction of cytokines such as CXCL10 or IL6. Single cell RNA sequencing data showed that canonical interferon stimulated genes such as IFIT2 or OAS2 were broadly induced, whereas interferon beta (IFNB1) and lambda (IFNL1-4) were expressed only in a subset of infected cells. In addition, temporal resolution of transcriptional responses suggested interferon regulatory factors (IRFs) activities precede that of nuclear factor-κB (NF-κB). Lastly, we identified heat shock protein 90 (HSP90) as a protein relevant for the infection. Inhibition of the HSP90 charperone activity by Tanespimycin/17-N-allylamino-17-demethoxygeldanamycin (17-AAG) resulted in a reduction of viral replication, and of TNF and IL1B mRNA levels. In summary, our study established in vitro cell culture models to study SARS-CoV-2 infection and identified HSP90 protein as potential drug target for therapeutic intervention of SARS-CoV-2 infection.
  - **Dataset link:** GSE148729
  - **Sharing statement:** Raw sequencing is available at the Gene Expression Omnibus database (GEO), identifier GSE148729 (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE148729). Supplementary data and supporting files such as scRNA-seq Seurat objects are available at www.mdc-berlin.de/singlecell-SARSCoV2.
<br/>

- <a name="14_long"></a>[:arrow_left: Back to the list](#14_short)
- [Immunologic perturbations in severe COVID-19/SARS-CoV-2 infection](https://doi.org/10.1101/2020.05.18.101717)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** AIRR
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.05.18.101717
  - **Publication abstract\Press release:** Although critical illness has been associated with SARS-CoV-2-induced hyperinflammation, the immune correlates of severe COVID-19 remain unclear. Here, we comprehensively analyzed peripheral blood immune perturbations in 42 SARS-CoV-2 infected and recovered individuals. We identified broad changes in neutrophils, NK cells, and monocytes during severe COVID-19, suggesting excessive mobilization of innate lineages. We found marked activation within T and B cells, highly oligoclonal B cell populations, profound plasmablast expansion, and SARS-CoV-2-specific antibodies in many, but not all, severe COVID-19 cases. Despite this heterogeneity, we found selective clustering of severe COVID-19 cases through unbiased analysis of the aggregated immunological phenotypes. Our findings demonstrate broad immune perturbations spanning both innate and adaptive leukocytes that distinguish dysregulated host responses in severe SARS-CoV-2 infection and warrant therapeutic investigation.
  - **Dataset link:** PRJNA630455
  - **Sharing statement:** Data and materials availability: All data associated with this study are present in the paper or the Supplementary Materials. The immunoglobulin heavy chain sequencing data is being submitted in an AIRR-compliant manner to SRA under PRJNA630455.
<br/>

- <a name="15_long"></a>[:arrow_left: Back to the list](#15_short)
- [Identification of Candidate COVID-19 Therapeutics using hPSC-derived Lung Organoids](https://doi.org/10.1101/2020.05.05.079095)
  - **Data public availability:** :heavy_check_mark: Available
  - **Data type:** scRNAseq
  - **Source type:** Publication
  - **Publication DOI:** https://doi.org/10.1101/2020.05.05.079095
  - **Publication abstract\Press release:** The SARS-CoV-2 virus has caused already over 3.5 million COVID-19 cases and 250,000 deaths globally. There is an urgent need to create novel models to study SARS-CoV-2 using human disease-relevant cells to understand key features of virus biology and facilitate drug screening. As primary SARS-CoV-2 infection is respiratory-based, we developed a lung organoid model using human pluripotent stem cells (hPSCs) that could be adapted for drug screens. The lung organoids, particularly aveolar type II cells, express ACE2 and are permissive to SARS-CoV-2 infection. Transcriptomic analysis following SARS-CoV-2 infection revealed a robust induction of chemokines and cytokines with little type I/III interferon signaling, similar to that observed amongst human COVID-19 pulmonary infections. We performed a high throughput screen using hPSC-derived lung organoids and identified FDA-approved drug candidates, including imatinib and mycophenolic acid, as inhibitors of SARS-CoV-2 entry. Pre- or post-treatment with these drugs at physiologically relevant levels decreased SARS-CoV-2 infection of hPSC-derived lung organoids. Together, these data demonstrate that hPSC-derived lung cells infected by SARS-CoV-2 can model human COVID-19 disease and provide a valuable resource to screen for FDA-approved drugs that might be repurposed and should be considered for COVID-19 clinical trials.
  - **Dataset link:** GSE148697
  - **Sharing statement:** RNA-seq data is available from the GEO repository database with accession number GSE148697.
<br/>



# License
The project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Terms of use
This is a COVID19 research view of [ImmunoMind](https://immunomind.io) team. We provide the view freely and openly to the research and drug discovery community to support them in the battle against COVID19.
This is a public resource and we encourage the COVID19 research community to [input](contributing.md).


