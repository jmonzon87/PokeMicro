# PokeMicro

Code for the analysis of single cell RNA-seq data from induced Pluripotent Stem Cell derived microglia (iPSC-micro).

### Data availability

+ Raw and processed gene expression data has been deposited in GEO [GSE186301](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE186301).

### To start

Download gene expression data and metadata.
+ Counts: [GSE186301_Counts_ProteinCodingGenes.txt](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE186301&format=file&file=GSE186301%5FCounts%5FProteinCodingGenes%2Etxt%2Egz)
+ Metadata: [GSE186301_Metadata.txt.gz](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE186301&format=file&file=GSE186301%5FMetadata%2Etxt%2Egz)

### Gene lists

We have also included relevant gene lists in 00_Data

+ Core Microglia signature (Microglia_CoreSignature_2018_Patir.txt)
+ Genes associated to AD from GWAS (ADgwas)
+ Genes differentially expressed in microglia from AD patients (ADdegs)

### RMarkdown files

+ iPSCmicro.Rmd Overview of the gene expression data. Normalization, scaling, clustering, PCA, UMAP, differential expression and gene ontology analysis.

### License

Distributed under the MIT License. See `License.txt` for more information.
