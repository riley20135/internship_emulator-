**The KSQ**
The objective of this project is determining the efficacy of Trastuzumab and Bevacizumab in other cancers beyond their common uses. A preliminary step for this will be determining the expression levels of the target genes (HER2 and VEGF) within these cancer cells lines, based on their scRNA-seq data. Cancer cell lines serve as a robust model system to determine the efficacy of anti cancer drugs by providing a homogenous, regulated cell population for testing and analysis. 

**What is scRNA, and why use it?**
As noted in Haque et. al (2017), scRNA "permits comparison of the transcriptomes of individual cells." In this case, the "transcriptome" is the specific analysis of how DNA is _expressed_ as proteins and other molecules by quantifying all of the mRNA (aka the genetic sequence of a gene). Therefore, it can be used on an individual cell level to determine expression levels of our target genes 

**Why use Cancer Cell Lines?**
Cancer cell lines are lines of cells that when taken care of under the correct controls, are not only immortal, but can retain many of the characteristics of the original cancer that they came from. Paired with -omics analysis or in our case, scRNA-seq data, the "driver mutations" can be more easily determined, and these results can be replicated due to the nature of the cancer cell line. Despite this importance, there are challenges with forming, maintaining, and utilizing cancer cell lines. From a technical perspective, growing cancer cell lines has a variety of challenges including isolating the cells and cell culture. Biologically, they can undergo genetic drift which makes the cell line less stable and/or useful, and there is a lack of influence from cell signaling molecules, which do have a role in cancer metastasis.

**Mechanism of Action — Trastuzumab**
Trastuzumab is used in the treatment of HER2-positive breast and gastric cancers. HER2, a transmembrane tyrosine kinase receptor, is overexpressed in "20%-30% of invasive breast carcinomas" hence its use as a target for cancer treatments. HER2 functions by dimerizing with another HER receptor (1-4), and this activates a signal transduction cascade through the RAS-MAPK pathway, a cell proliferation pathway. Trastuzumab binds to the extracellular domain of the HER2 receptor, and the most popular mechanism proposal is that it prevents hetero/homodimerization, therefore deactivating the signaling cascade for cell proliferation. 

**Mechanism of Action — Bevacizumab**
Bevacizumab is used for a variety of cancers (ie: colorectal, lung, glioblastoma, breast, liver, and kidney cancer.) and targets VEGF. VEGF is a growth factor, and when bound to it's receptor (VEGF receptor), promotes angiogenesis via the "recruitment and proliferation of endothelial cells." Bevacizumab acts by selectively binding to circulating VEGF, making it unable to bind to it's receptors, and thereby leading to a reduction in blood supply to the tumor.  A potential weakness of using cell lines (versus an in vivo model) to test bevacizumab is that cell lines cannot replicate angiogenesis, since these cells will not form new blood vessels. 

Filis Kazazi-Hyseni, Jos H. Beijnen, Jan H. M. Schellens, Bevacizumab, The Oncologist, Volume 15, Issue 8, August 2010, Pages 819–825, https://doi.org/10.1634/theoncologist.2009-0317

Haque, A., Engel, J., Teichmann, S.A. et al. A practical guide to single-cell RNA-sequencing for biomedical research and clinical applications. Genome Med 9, 75 (2017). https://doi.org/10.1186/s13073-017-0467-4

Hudis, Clifford A. "Trastuzumab — Mechanism of Action and Use in Clinical Practice." New England Journal of Medicine, vol. 357, no. 1, 2007, pp. 39-51. DOI: 10.1056/NEJMra043186.

Idrisova KF, Simon HU, Gomzikova MO. Role of Patient-Derived Models of Cancer in Translational Oncology. Cancers (Basel). 2022 Dec 26;15(1):139. doi: 10.3390/cancers15010139. PMID: 36612135; PMCID: PMC9817860.

Mirabelli P, Coppola L, Salvatore M. Cancer Cell Lines Are Useful Model Systems for Medical Research. Cancers (Basel). 2019 Aug 1;11(8):1098. doi: 10.3390/cancers11081098. PMID: 31374935; PMCID: PMC6721418.

National Zoo. "Center for Conservation Genomics." Smithsonian's National Zoo & Conservation Biology Institute. Accessed July 23, 2024. https://nationalzoo.si.edu/center-for-conservation-genomics/genomics

News Medical. "Why are Cancer Cell Lines Useful?" News-Medical.net. Accessed July 23, 2024. https://www.news-medical.net/life-sciences/Why-are-Cancer-Cell-Lines-Useful.aspx.
_______________________________________________________________
**Paper Analysis**
1. How did the authors handle the potential caveat of co-culturing cell lines before profiling by scRNA-seq? Why do you think that caveat was or was not adequately addressed?

  The authors conducted control experiments comparing gene expression in cell lines with and without co-culturing, finding that co-culturing had a modest effect on average gene expression but did not significantly alter patterns of heterogeneity within cell lines. This suggests that the caveat was adequately addressed, as the core findings remained consistent across conditions.

2. The authors identified discrete subpopulations of cells within a subset of individual cell lines (Fig. 2A-B). What might be the reason why some cell lines have these discrete subpopulations while others do not?

  The presence of discrete subpopulations in some cell lines may be due to inherent genetic or epigenetic variability, differences in microenvironmental influences, or specific adaptations to culture conditions, which may not be uniformly present across all cell lines.

3. What are Recurrent Heterogeneous Programs (RHPs) and how were they defined?

  RHPs are defined as gene expression programs that exhibit variability across multiple cell lines, identified through non-negative matrix factorization (NMF) and hierarchical clustering. They represent common patterns of gene expression that are robustly detected across different contexts.

4. How do the identified RHPs relate to in vivo programs of heterogeneity in tumors, and what evidence supports this relationship?

  The identified RHPs showed significant overlap with in vivo expression programs from patient tumors, supported by high correlation of signature genes and cell scores between in vitro and in vivo datasets, indicating their relevance to tumor heterogeneity.

5. Where can you download the scRNA-seq data as shown in Figure 1B?

  At the Gene Expression Omnibus (GEO) (accession number GSE157220) as mentioned in the "Data Avaliability" section 







