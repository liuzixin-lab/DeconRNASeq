# DeconRNASeq-Deconvolution
*For heterogeneous tissues, measurements of gene expression through mRNA-Seq data are confounded by relative proportions of cell types involved. In this note, we introduce an efficient pipeline: DeconRNASeq, an R package for deconvolution of heterogeneous tissues based on mRNA-Seq data. It adopts a globally '''optimized non-negative decomposition algorithm through quadratic programming''' for estimating the mixing proportions of distinctive tissue types in next-generation sequencing data. We demonstrated the feasibility and validity of DeconRNASeq across a range of mixing levels and sources using mRNA-Seq data mixed in silico at known concentrations. We validated our computational approach for various benchmark data, with high correlation between our predicted cell proportions and the real fractions of tissues. Our study provides a rigorous, quantitative and high-resolution tool as a prerequisite to use mRNA-Seq data. The modularity of package design allows an easy deployment of custom analytical pipelines for data from other high-throughput platforms.
 
