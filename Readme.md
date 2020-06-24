The central dogma of molecular biology describes the two-step process, transcription and translation, by which the information in genes flows into proteins: DNA ? RNA ? protein. Transcription is the synthesis of an RNA copy of a segment of DNA. RNA is synthesized by the enzyme RNA polymerase.

Besides mRNA, tRNA and rRNA which are important for protein synthesis, there are many other types of RNA that play a huge roll in the regulatory programms of cells.

single-cell RNA-sequencing is a technique where the expression of RNA in single cells can be measured.

Measuring and analyzing such data can give insights in for example celltype specific regulation and can help to understand the progress of deseases.

Imputation is the process of replacing missing data with substitute values.

In scRNAseq protocols that measure the expression, dropout events can happen. Although RNA molecules are expressed in the cell, due to protocol specific or other factors, these molecules arent captured and thus cant be measured.

This project is inspired by:

<a id="1">1</a> Li, W.V., Li, J.J. An accurate and robust imputation method scImpute for single-cell RNA-seq data. Nat Commun 9, 997 (2018).

<a id="2">2</a> M.D. Luecken, F.J. Theis, "Current best practices in single-cell RNA-seq analysis: a tutorial", Molecular Systems Biology 15(6) (2019)

<a id="3">3</a> Zheng, G., Terry, J., Belgrader, P. et al. Massively parallel digital transcriptional profiling of single cells. Nat Commun 8, 14049 (2017).

For this project single-cell RNA-sequencing data is analysed with state of the art methods described in 
<a href=#2> (2) </a> and shown in a [complementary tutorial](https://github.com/theislab/single-cell-tutorial/) using the [scanpy library](https://scanpy.readthedocs.io/en/stable/index.html).
I want to compare the results of a basic workflow for raw/filtered and imputated single cell expression data, on the example of scImpute <a href=#1> (1) </a> with [single-cell RNA-sequencing data](https://support.10xgenomics.com/single-cell-gene-expression/datasets) provided in scope of <a href=#3> (3) </a>