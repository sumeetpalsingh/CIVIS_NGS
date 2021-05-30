# Glossary of Terms

**CPM**: Counts per million. A method for normalization of RNA-Seq data that takes into account the depth of the library. Library depth is the sum of all counts (reads) in a sample. 

**[FDR](https://en.wikipedia.org/wiki/False_discovery_rate)**: A statistical test performed on p-value to remove potential false-positives. For example, a p-value of 0.05 implies that there is 5% chance of a gene to show differential expression, even if the gene expression does not change. If there are 30,000 genes, this means that 0.05 * 30,000 = 1,500 genes that appear to be differentially expressed, even though their expression does not change. FDR attempts to locate such genes and remove them from significance.

**[GEO](https://www.ncbi.nlm.nih.gov/geo/)**: Gene Expression Omnibus, a repository of publicly available datasets.

**GO**: Gene ontology. A analysis tools that attempts to provide functional characterization for a set of genes based on the exisiting information about their biological role. The functional information can help understand the pathways that change upon treatment. 

**RPKM**: Reads per kilobase (kb) per million. A method for normalization of RNA-Seq data that takes into account the size of the gene and the depth of the library.

**RPM**: Reads per million. A method for normalization of RNA-Seq data that takes into account the depth of the library. (Note: This is same as CPM; counts and reads are interchaneably used).

**[Volcano Plot](https://en.wikipedia.org/wiki/Volcano_plot_(statistics))**: A plotting tool to present the results of RNA-Seq data. In this, log2(p-value / false discovery rate) (X-axis) is plotted against the negative log10 of fold-change.
