# **Identification of Early-Stage Biomarkers for Hepatocellular Carcinoma (HCC)** 

## **Overview**

This project focuses on identifying potential early-stage biomarkers for hepatocellular carcinoma (HCC) using gene expression data. The study leverages datasets from the Gene Expression Omnibus (GEO) to analyze differential gene expression between fetal liver, adult liver, and HCC samples. The goal is to identify genes associated with the dedifferentiation process, a hallmark of early-stage HCC.  

## **Methodology** 

The analysis follows these key steps: 

1. **Data Acquisition**: Microarray datasets were obtained from the GEO database, including fetal liver, adult liver, and HCC tissue samples. 

2. **Preprocessing**: The data was log2-transformed and normalized to ensure comparability across samples.

3. **Group Analysis**: Differential gene expression analyses were conducted using UMAP plots, volcano plots, and Venn diagrams for the following groups: 

      - Group 1: Annotated early-stage HCC samples. 

      - Group 2: Healthy liver tissues vs. adjacent non-       tumor tissues of HCC. 

      - Group 3: HCC tumor tissues vs. adjacent non-       tumor tissues. 

      - Group 4: Fetal liver vs. adult liver samples. 

4. **Enrichment Analysis**: Identified genes underwent enrichment analysis to reveal their involvement in HCC-related pathways. 

5. **Key Findings**: The analysis identified three key genes—SQLE, AFP, and COL2A1—as potential early-stage HCC biomarkers. 

## **Results Summary** 

- **UMAP Plots**: Showed clustering patterns among the various tissue groups, highlighting similarities between fetal liver and adult liver tissues in early-stage HCC. 

- **Volcano Plots**: Revealed significant differentially expressed genes (DEGs) across the groups, with key genes identified for further analysis. 

- **Venn Diagrams**: Used to identify common genes between the datasets, leading to the selection of SQLE, AFP, and COL2A1 as potential biomarkers. 

- **Enrichment Analysis**: Supported the involvement of the identified genes in HCC-related pathways, highlighting their potential as early diagnostic markers. 

## **References**

- Bashur, L.A., Chen, D., Chen, Z., Liang, B., Pardi, R., Murakami, S. and Zhou, G. (2018). Loss of jab1 in osteochondral progenitor cells severely impairs embryonic limb development in mice. Journal of Cellular Physiology, [online] 229(11), pp.1607–1617. doi:10.1002/jcp.24602.image.pngimage.pngimage.pngimage.png
- Luo, P., Wu, S., Yu, Y., Ming, X., Li, S., Zuo, X. and Tu, J. (2019). Current Status and Perspective Biomarkers in AFP Negative HCC: Towards Screening for and Diagnosing Hepatocellular Carcinoma at an Earlier Stage. Pathology & Oncology Research. doi:10.1007/s12253-019-00585-5.
- Shi, J.-F., Cao, M., Wang, Y., Bai, F.-Z., Lei, L., Peng, J., Feletto, E., Canfell, K., Qu, C. and Chen, W. (2021). Is it possible to halve the incidence of liver cancer in China by 2050? International Journal of Cancer, [online] 148(5), pp.1051–1065. doi:10.1002/ijc.33313.image.pngimage.pngimage.pngimage.png
- Suhail, Y., Cain, M.P., Vanaja, K., Kurywchak, P.A., Levchenko, A., Kalluri, R. and Kshitiz (2019). Systems Biology of Cancer Metastasis. Cell Systems, [online] 9(2), pp.109–127. doi:10.1016/j.cels.2019.07.003.image.pngimage.pngimage.pngimage.png
- Yang, J.D., Hainaut, P., Gores, G.J., Amadou, A., Plymoth, A. and Roberts, L.R. (2019). A global view of hepatocellular carcinoma: trends, risk, prevention and management. Nature Reviews Gastroenterology & Hepatology, 16(10), pp.589–604. doi:10.1038/s41575-019-0186-y.image.pngimage.pngimage.pngimage.png
- Yin, W., zhang, Wu, W., Jiao, H., Chen, Y., Ji, X., Cao, J. and Yin, F. (2022). Squalene epoxidase promotes hepatocellular carcinoma development by activating STRAP transcription and TGF-β/SMAD signaling. 1. doi:10.22541/au.164201880.00585800/v1.image.pngimage.pngimage.pngimage.png
