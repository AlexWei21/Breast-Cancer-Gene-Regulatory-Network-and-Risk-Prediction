# **Gene Regulatory Network and Cancer Prediction in Breast Cancer**

Group Member: Jinglun Li, Yidan Ma, Zhengkuan Tang, Ziming Wei

## Background

Breast Cancer is one of the most common cancers in the world. According to the National Breast Cancer Foundation, there was an estimated 281,550 new cases of invasive breast cancers in the U.S. in 2021, and an estimated number of 43,600 women died from breast cancer in the U.S. [1] The huge population of breast cancer is a huge driving force for breast cancer research both in dry lab and wet lab. Though there were already a lot of researches done in discovering the mechanism of breast cancer, most of them were conducted in the wet lab and couldn&#39;t completely explain the mechanism of breast cancer at a genomic level. Most of the therapeutics now are still through surgeries, and according to the Cancer Treatment Centers of America, leads to an average of 7 percent to 11 percent Recurrent Rate of Breast Cancer. [2] In order to decrease the rate of recurrence, we have to create a gene network and use machine learning algorithms to find out important target genes for possible gene therapies for Breast Cancer.

## Section Overview

- **Differential Gene Expression (DGE) Analysis**

In order to figure out the genes that are crucial for the development of breast cancer, we conducted a differential gene expression analysis. The analysis focused on finding out the genes that are differentially expressed between cancer samples and normal samples. The filtered out genes may indicate that they perform an important role in promoting or recessing the development of breast cancer.

- **Data Preprocessing and Gene Ontology Enrichment Analysis**

After identifying differentially expressed genes, Gene Ontology Enrichment Analysis was performed to find out the significant pathways to which the differentially expressed genes belong. The GO Enrichment Analysis could both help to validate the result of Differential Gene Expression Analysis and discover possible pathways for future gene therapies to target. The methods and visualizations for data preprocessing could be found in this module as well. Raw data was scaled, ID converted, and visualized to facilitate future analysis.

- **ML-Based Feature Selection and Predictive Model Construction**

After data pre-processing, a basic clustering algorithm is used to determine if the samples from the dataset are clustered into several categories. Then, several ML-based methods were applied to find out important genes that support the classification of breast cancer subtypes. After that, an ML-based prediction model was built on the selected genes to model the relationship between the gene expression level and different types of breast cancer.

- **Biological Network**

After getting two parallel sets of genes: differentially expressed genes and machine learning selected genes, top genes for each panel were analyzed in the network context. With appropriate threshold for nodes and edges, two main gene networks were constructed. Networks with breast cancer association information were visualized to represent the characteristics of two sets. Hubs were identified in both networks, where the common hubs were regarded as a main result of the whole project.

#

# Reference

Breast cancer information, support &amp;amp; donations. National Breast Cancer Foundation. (2022, May 10). Retrieved May 13, 2022, from [http://www.nationalbreastcancer.org/](http://www.nationalbreastcancer.org/) [1]

Recurrent breast cancer. Cancer Treatment Centers of America. (2022, May 5). Retrieved May 13, 2022, from [https://www.cancercenter.com/cancer-types/breast-cancer/types/rare-breast-cancer-types/recurrent-breast-cancer](https://www.cancercenter.com/cancer-types/breast-cancer/types/rare-breast-cancer-types/recurrent-breast-cancer) [2]

Gruosso T, Mieulet V, Cardon M, Bourachot B et al. Chronic oxidative stress promotes H2AX protein degradation and enhances chemosensitivity in breast cancer patients. EMBO Mol Med 2016 May;8(5):527-49. PMID: 27006338 [3]

Love, M.I., Huber, W. &amp; Anders, S. Moderated estimation of fold change and dispersion for RNA-seq data with DESeq2. Genome Biol 15, 550 (2014).[https://doi.org/10.1186/s13059-014-0550-8](https://doi.org/10.1186/s13059-014-0550-8). [4]

Gautier L, Cope L, Bolstad BM, Irizarry RA (2004). &quot;affy—analysis of Affymetrix GeneChip data at the probe level.&quot; Bioinformatics, 20(3), 307–315. ISSN 1367-4803, doi: 10.1093/bioinformatics/btg405. [5]

Wan C, Borgeson B, Phanse S, Tu F, Drew K, Clark G, Xiong X, Kagan O, Kwan J, Bezginov A, Chessman K, Pal S, Cromar G, Papoulas O, Ni Z, Boutz DR, Stoilova S, Havugimana PC, Guo X, Malty RH, Sarov M, Greenblatt J, Babu M, Derry WB, Tillier ER, Wallingford JB, Parkinson J, Marcotte EM, Emili A. Panorama of ancient metazoan macromolecular complexes. Nature. 2015 Sep 17;525(7569):339-44. doi: 10.1038/nature14877. Epub 2015 Sep 7. PMID: 26344197; PMCID: PMC5036527. [6]

Dubern B, Clement K. Leptin and leptin receptor-related monogenic obesity. Biochimie. 2012 Oct;94(10):2111-5. doi: 10.1016/j.biochi.2012.05.010. Epub 2012 May 22. PMID: 22627381. [7]

Feltes, B.C.; Chandelier, E.B.; Grisci, B.I.; Dorn, M. (2019) CuMiDa: An Extensively Curated Microarray Database for Benchmarking and Testing of Machine Learning Approaches in Cancer Research. Journal of Computational Biology, 26 (4), 376-386. [[https://doi.org/10.1089/cmb.2018.0238](https://doi.org/10.1089/cmb.2018.0238)] [8]

[Scikit-learn: Machine Learning in Python](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html), Pedregosa et al., JMLR 12, pp. 2825-2830, 2011. [9]

B.T. Sherman, M. Hao, J. Qiu, X. Jiao, M.W. Baseler, H.C. Lane, T. Imamichi and W. Chang. DAVID: a web server for functional enrichment analysis and functional annotation of gene lists (2021 update). Nucleic Acids Research. 23 March 2022. doi:10.1093/nar/gkac194.[[PubMed](https://pubmed.ncbi.nlm.nih.gov/35325185/)] [10]

Huang DW, Sherman BT, Lempicki RA. Systematic and integrative analysis of large gene lists using DAVID Bioinformatics Resources. Nature Protoc. 2009;4(1):44-57. [[PubMed](http://www.ncbi.nlm.nih.gov/pubmed/19131956?dopt=Abstract)] [11]

Damian Smedley, Syed Haider, Steffen Durinck, et al. The BioMart community portal: an innovative alternative to large, centralized data repositories, Nucleic Acids Research, Volume 43, Issue W1, 1 July 2015, Pages W589–W598, [https://doi.org/10.1093/nar/gkv350](https://doi.org/10.1093/nar/gkv350) [12]

Eran Eden\*, Roy Navon\*, Israel Steinfeld, Doron Lipson and Zohar Yakhini. &quot;GOrilla: A Tool For Discovery And Visualization of Enriched GO Terms in Ranked Gene Lists&quot;, [BMC Bioinformatics 2009, 10:48](http://www.biomedcentral.com/1471-2105/10/48). [13]

Eran Eden, Doron Lipson, Sivan Yogev, Zohar Yakhini. &quot;Discovering Motifs in Ranked Lists of DNA sequences&quot;, [PLoS Computational Biology](http://compbiol.plosjournals.org/perlserv/?request=get-document&amp;doi=10.1371/journal.pcbi.0030039), 3(3):e39, 2007. [14]

Davidson, I., Ravi, S.S., 2005. Agglomerative Hierarchical Clustering with Constraints: Theoretical and Empirical Results, in: Advanced Data Mining and Applications. Advanced Data Mining and Applications, pp. 59–70.. doi:10.1007/11564126\_11 [15]

Zeng, X., Chen, Y.-W., Tao, C., 2009. Feature Selection Using Recursive Feature Elimination for Handwritten Digit Recognition, in: .. doi:10.1109/iih-msp.2009.145 [16]

Hirukawa, A., Smith, H.W., Zuo, D., Dufour, C.R., Savage, P., Bertos, N., Johnson, R.M., Bui, T., Bourque, G., Basik, M., Giguère, V., Park, M., Muller, W.J., 2018. Targeting EZH2 reactivates a breast cancer subtype-specific anti-metastatic transcriptional program. Nature Communications 9.. doi:10.1038/s41467-018-04864-8 [17]

Zhou, W., Fang, C., Zhang, L., Wang, Q., Li, D., &amp; Zhu, D. (2020). Thioredoxin domain-containing protein 9 (TXNDC9) contributes to oxaliplatin resistance through regulation of autophagy-apoptosis in colorectal adenocarcinoma. Biochemical and biophysical research communications.[18]

Franke, C.M., Gu, V.W., Grimm, B.G., Cassady, V.C., White, J.R., Weigel, R.J., Kulak, M.V., 2020. TFAP2C regulates carbonic anhydrase XII in human breast cancer. Oncogene 39, 1290–1301.. doi:10.1038/s41388-019-1062-5[19]

Seo, Chang H., et al. &quot;Hub genes with positive feedbacks function as master switches in developmental gene regulatory networks.&quot; Bioinformatics 25.15 (2009): 1898-1904.[20]

Liu, Yang, et al. &quot;Identification of hub genes and key pathways associated with bipolar disorder based on weighted gene co-expression network analysis.&quot; Frontiers in physiology (2019): 1081.[21]

Deng, J. L., Y. H. Xu, and G. Wang. &quot;Identification of potential crucial genes and key pathways in breast cancer using bioinformatic analysis. Front Genet 10: 695.&quot; (2019).[22]

Wang, Dongdong, et al. &quot;Anillin regulates breast cancer cell migration, growth, and metastasis by non-canonical mechanisms involving control of cell stemness and differentiation.&quot; Breast Cancer Research 22.1 (2020): 1-19.[23]

Magnusson, Kristina, et al. &quot;ANLN is a prognostic biomarker independent of Ki-67 and essential for cell cycle progression in primary breast cancer.&quot; Bmc Cancer 16.1 (2016): 1-13.[24]

Lin, Tong, et al. &quot;Heat shock protein 90 family isoforms as prognostic biomarkers and their correlations with immune infiltration in breast cancer.&quot; BioMed research international 2020 (2020).[25]

Sunil Kumar, B. V., et al. &quot;The overexpression of Hsp90B1 is associated with tumorigenesis of canine mammary glands.&quot; Molecular and Cellular Biochemistry 440.1 (2018): 23-31.[26]
