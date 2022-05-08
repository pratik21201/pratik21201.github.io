---
title: "Davuluri Lab - Research"
layout: textlay
excerpt: "Davuluri Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

The central hypothesis of our laboratory is that the isoform-level gene products “transcript variants” and “protein isoforms” are the basic functional units in the mammalian cell, and accordingly, the informatics platforms – ranging from basic molecular biology data management systems to the biomarker and therapeutic drug target discovery for precision medicine – should adapt “gene isoform centric” rather than “gene centric” approaches. 

Our research is focused on developing statistical machine learning based algorithms and informatics solutions for knowledge extraction in biology and medicine. Our ongoing research work, funded by National Library of Medicine/NIH R01, focuses on developing novel bioinformatics methods to help in silico discovery and research for accelerating the linkage of phenotypic and genomic information at gene-isoform level. The overarching goal of the lab is to translate data from high dimensional (-omic) platforms (e.g., NextGen sequencing) to derive experimentally interpretable and testable discovery models for the identification and characterization of transcript-variants/protein isoforms, networks and pathways involved in normal and disease cells. Our data science group collaborates with experimental and clinical researchers towards identification of genetic and epigenetic signatures for identification of subsets of cancer patients who may benefit from therapeutic intervention and guide the understanding of drug activity in patient tumors, towards the goals of precision medicine (for example, [Platform-Independent Classification System to Predict Molecular Subtypes of High-Grade Serous Ovarian Carcinoma](https://pubmed.ncbi.nlm.nih.gov/31002564/))


Summary of Ongoing and Past Research Projects:

**DNABERT: A pre-trained Bidirectional Encoder Representations from Transformers model for DNA-language in genome:** 

![]({{ site.url }}{{ site.baseurl }}/images/respic/dnabert.jpg){: style="width: 70%; float: center; margin: 10px"}

Understanding the hidden instructions within genome on gene regulation is crucial for biological research. However, complex language patterns widely exist in DNA, such as polysemy and distant semantic relationship, which previous methods often fail to capture especially in data-scarce scenarios. For the first time, our group (in collaboration with [Dr Han Liu, Department of Computer Science, Northwestern University] (http://magics.cs.northwestern.edu/index.html)) is developing DNABERT to form global understanding of genomic sequences based on up and downstream sequence contexts. Using an innovative global contextual embedding of input sequences, DNABERT attempts to tackle the problem of sequence specificity prediction with a “top-down” approach by developing general understanding of DNA language via self-supervised pre-training and applying it to specific tasks (for example, prediction of promoters, transcription factor binding sites and splice sites), in contrast to the traditional “bottom-up” approach using task-specific data. Various modules of DNABERT are currently under development. It is anticipated that the pre-trained DNABERT on the human genome can also be readily applied to data from other organisms with exceptional performance.

**Isoform-level gene expression and regulation in mammalian development and cancer:** Recent genome-wide studies have discovered that majority of human genes produce multiple transcript-variants/protein-isoforms, which could be involved in different functional pathways. Moreover, altered expression of specific isoforms for numerous genes is linked with cancer and its prognosis, as cancer cells manipulate regulatory mechanisms to express specific isoforms that confer drug resistance and survival advantages. For example, cancer-associated alterations in alternative exons and splicing machinery have been identified in cancer samples, suggesting that specific transcript-variants could be more effective as diagnostic and prognostic markers than corresponding genes. In a recent study, Davuluri group discovered that majority of genes associated with neurological diseases expressed multiple transcripts through alternative promoters by using integrative NextGen sequencing based experimental approaches and bioinformatics analysis. The study also observed aberrant use of alternative promoters and splice variants in different cancers. Subsequently, his group demonstrated that cancer cell-lines regardless of their tissue of origin can be effectively discriminated from non-cancer cell-lines at isoform-level, but not at gene-level. The novel informatics methods have been successfully applied by his collaborators in different cancer studies.

**Platform-independent isoform-level gene signatures for stratification of cancer patients into molecular subgroups:** 

![]({{ site.url }}{{ site.baseurl }}/images/respic/pigex.jpg){: style="width: 70%; float: center; margin: 10px"}

Based on recent studies from Davuluri group and others, significant expression differences were observed between different sample groups (e.g., developmental stages, cancer subtypes, normal vs cancer) for numerous genes at the isoform-level but not at the overall gene-level. Davuluri group investigated whether the isoform-level transcriptome changes could provide better patient stratification in terms of overall prognosis and classification accuracy. His group developed novel methods, by integrating data discretization, feature selection, and meta-classification algorithms, for derivation of platform-independent gene signature for multi-label molecular stratification of cancer patients, from exon-array and RNA-seq data. The application of these algorithms has led to the development of new methods for diagnosis of glioblastoma and other cancers and investigation of alternative splicing on drug-target gene interactions.

**Algorithms and bioinformatics software for analyses of NextGen sequence data:** Mapping genome-wide data to human subtelomeres has been problematic due to the incomplete assembly and challenges of lowcopy repetitive DNA elements. Davuluri group developed novel bioinformatics pipelines for incorporating multi-read mapping for annotation of the updated assemblies using short-read data sets from ChIP-seq data, and RNA-seq data. As part of other collaborative efforts, his group developed bioinformatics methods for identification of single-nucleotide polymorphisms (SNPs) that alter miRNA gene regulation and influence tumor susceptibility. Similarly, his group played a pivotal role in the development of informatics methods required for analysis of small-RNA sequence data, with Nishikura group at Wistar Institute, Philadelphia, PA.


![]({{ site.url }}{{ site.baseurl }}/images/respic/SmartTip.png){: style="width: 250px; float: left; margin: 0px  10px"}


