---
title: "HLi Lab - Software"
layout: textlay
excerpt: "Software and Resources"
sitemap: false
permalink: /software
---

## Software and Resources

Our lab developed several alignment and assembly algorithms critical to high-throughput sequence analysis.
These include [samtools][sw-samtools], [BWA][sw-bwa], [minimap2][sw-minimap2] and [hifiasm][sw-hifiasm],
with each cited for 1000+ times *per year*.
We also explore a variety of algorithms related to
variant calling (e.g. longcallR and longcallD),
pangenome analysis (e.g. minigraph and pangene),
protein alignment (e.g. miniprot),
full-text indexing (e.g. ropebwt3),
immunology (e.g. Immuannot and T1K),
evolution (e.g. psmc and compleasm)
and high-performance data structures in general (e.g. bedtk and BGT).
Most of our tools work years after their initial publications and are often well received.

### Software

#### Current

* [Breakinator][sw-breakinator]: detecting foldback artifacts in long reads, published in [Heinz et al (2026)][sw-breakinator]
  <img style="margin: 0px" src="https://img.shields.io/github/stars/jheinz27/breakinator"/>
  <a href="https://bioconda.github.io/recipes/breakinator/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/breakinator.svg?style=flag&label=Bioconda"/></a>
* [myloasm][sw-myloasm]: metagenome assembler for PacBio HiFi and Nanopore R10 reads, preprinted in [Shaw et al (2025)][pub-myloasm]
  <img style="margin: 0px" src="https://img.shields.io/github/stars/bluenote-1577/myloasm"/>
  <a href="https://bioconda.github.io/recipes/myloasm/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/myloasm.svg?style=flag&label=Bioconda"/></a>
* [longdust][sw-longdust]: identifying long STRs, VNTRs, satellite DNA and other low-complexity regions, preprinted in [Li (2025)][pub-longdust]
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/longdust"/>
  <a href="https://bioconda.github.io/recipes/longdust/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/longdust.svg?style=flag&label=Bioconda"/></a>
* [minisplice][sw-minisplice]: splice site scoring for improving spliced alignment, preprinted in [Yang et al (2025)][pub-minisplice]
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/minisplice"/>
  <a href="https://bioconda.github.io/recipes/minisplice/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/minisplice.svg?style=flag&label=Bioconda"/></a>
* [longcallD][sw-longcallD]: small and large variant calling from long genomic reads, unpublished
  <img style="margin: 0px" src="https://img.shields.io/github/stars/yangao07/longcallD"/>
  <a href="https://bioconda.github.io/recipes/longcalld/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/longcallD.svg?style=flag&label=Bioconda"/></a>
* [longcallR][sw-longcallR]: SNP calling and haplotype-specific analysis for long RNA-seq reads, preprinted in [Huang et al (2025)][pub-longcallR]
  <img style="margin: 0px" src="https://img.shields.io/github/stars/huangnengCSU/longcallR"/>
  <a href="https://bioconda.github.io/recipes/longcallr/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/longcallR.svg?style=flag&label=Bioconda"/></a>
* [colorSV][sw-colorsv]: somatic SV calling via tumor-normal co-assembly, published in [Le et al (2024)][pub-colorsv]
  <img style="margin: 0px" src="https://img.shields.io/github/stars/mktle/colorSV"/>
* [ropebwt3][sw-rb3]: construction and utility of BWT for DNA string sets, published in [Li (2014)][pub-rb2] and [Li (2024)][pub-rb3].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/ropebwt3"/>
  <a href="https://bioconda.github.io/recipes/ropebwt3/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/ropebwt3.svg?style=flag&label=Bioconda"/></a>
* [Immuannot][sw-immuannot]: annotating HLA and KIR genes in phased assemblies, published in [Zhou et al (2024)][pub-immuannot].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/YingZhou001/Immuannot"/>
* [pangene][sw-pangene]: constructing pangenome gene graphs, published in [Li (2024)][pub-pangene].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/pangene"/>
* [compleasm][sw-minibusco]: a reimplementation of BUSCO for evaluating the gene completeness of an assembly, published in [Huang and Li (2023)][pub-minibusco].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/huangnengCSU/compleasm"/>
  <a href="https://bioconda.github.io/recipes/compleasm/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/compleasm.svg?style=flag&label=Bioconda"/></a>
* [srf][sw-srf]: assembling satellite DNA, published in [Zhang et al (2023)][pub-srf].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/srf"/>
* [miniprot][sw-miniprot]: protein-to-genome alignment allowing splicing and frameshift, published in [Li (2023)][pub-miniprot].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/miniprot"/>
  <a href="https://bioconda.github.io/recipes/miniprot/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/miniprot.svg?style=flag&label=Bioconda"/></a>
* [bedtk][sw-bedtk] and [cgranges][sw-cgr]: a fast toolkit and library for working with BED files, published in [Li and Rong (2020)][pub-bedtk].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/bedtk"/>
  <a href="https://bioconda.github.io/recipes/bedtk/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/bedtk.svg?style=flag&label=Bioconda"/></a>
* [yak][sw-yak]: k-mer counting and assembly evaluation, developed for [Cheng et al (2021)][pub-ha1].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/yak"/>
  <a href="https://bioconda.github.io/recipes/yak/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/yak.svg?style=flag&label=Bioconda"/></a>
* [gwfa][sw-gwfa]: graph wavefront alignment with edit distance, preprinted at [Zhang et al (2022)][pub-gwfa].
  Merged into gfatools and used by minigraph.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/gwfa"/>
* [minigraph][sw-mg]: pangenome construction and sequence-to-graph alignment, published in [Li et al (2020)][pub-minigraph].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/minigraph"/>
  <a href="https://bioconda.github.io/recipes/minigraph/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/minigraph.svg?style=flag&label=Bioconda"/></a>
* [dipcall][sw-dipcall]: variant calling for phased diploid assemblies, developed for [Li et al (2019)][pub-dipcall].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/dipcall"/>
  <a href="https://bioconda.github.io/recipes/dipcall/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/dipcall.svg?style=flag&label=Bioconda"/></a>
* [minimap2][sw-minimap2]: widely used long-read aligner, published in [Li (2018)][pub-minimap2a] and improved in [Li (2021)][pub-minimap2b]
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/minimap2"/>
  <a href="https://bioconda.github.io/recipes/minimap2/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/minimap2.svg?style=flag&label=Bioconda"/></a>
  <a href="https://bioconda.github.io/recipes/mappy/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/mappy.svg?style=flag&label=mappy"/></a>
* [miniasm][sw-miniasm]: a simple long-read assembler, published in [Li (2016)][pub-miniasm].
  Useful for assembly at small scale; not recommended for production.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/miniasm"/>
  <a href="https://bioconda.github.io/recipes/miniasm/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/miniasm.svg?style=flag&label=Bioconda"/></a>
* [BWA][sw-bwa]: widely used short-read aligner,
  published in [Li and Durbin (2009)][pub-bwa1], [Li and Durbin (2010)][pub-bwa2] and [Li (2013)][pub-bwa3].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/bwa"/>
  <a href="https://bioconda.github.io/recipes/bwa/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/bwa.svg?style=flag&label=Bioconda"/></a>

[sw-breakinator]: https://github.com/jheinz27/breakinator
[pub-breakinator]: https://pubmed.ncbi.nlm.nih.gov/41495659/
[sw-longdust]: https://github.com/lh3/longdust
[pub-longdust]: https://arxiv.org/abs/2509.07357
[sw-colorsv]: https://github.com/mktle/colorSV
[pub-colorsv]: https://pubmed.ncbi.nlm.nih.gov/40973068/
[sw-minisplice]: https://github.com/lh3/minisplice
[pub-minisplice]: https://doi.org/10.48550/arXiv.2506.12986
[sw-myloasm]: https://github.com/bluenote-1577/myloasm
[pub-myloasm]: https://www.biorxiv.org/content/10.1101/2025.09.05.674543v1
[sw-longcallD]: https://github.com/yangao07/longcallD
[sw-longcallR]: https://github.com/huangnengCSU/longcallR
[pub-longcallR]: https://www.biorxiv.org/content/10.1101/2025.05.26.656191v1
[sw-cgr]: https://github.com/lh3/cgranges
[pub-miniasm]: https://pubmed.ncbi.nlm.nih.gov/27153593/
[sw-miniasm]: https://github.com/lh3/miniasm
[pub-bedtk]: https://pubmed.ncbi.nlm.nih.gov/32966548/
[sw-bedtk]: https://github.com/lh3/bedtk
[sw-yak]: https://github.com/lh3/yak
[pub-dipcall]: https://pubmed.ncbi.nlm.nih.gov/30013044/
[sw-dipcall]: https://github.com/lh3/dipcall
[sw-minimap2]: https://github.com/lh3/minimap2
[pub-minimap2a]: https://pubmed.ncbi.nlm.nih.gov/29750242/
[pub-minimap2b]: https://pubmed.ncbi.nlm.nih.gov/34623391/
[sw-bwa]: https://github.com/lh3/bwa
[sw-miniprot]: https://github.com/lh3/miniprot
[pub-miniprot]: https://pubmed.ncbi.nlm.nih.gov/36648328/
[pub-bwa1]: https://pubmed.ncbi.nlm.nih.gov/19451168/
[pub-bwa2]: https://pubmed.ncbi.nlm.nih.gov/20080505/
[pub-bwa3]: https://arxiv.org/abs/1303.3997
[pub-minibusco]: https://pubmed.ncbi.nlm.nih.gov/37758247/
[sw-minibusco]: https://github.com/huangnengCSU/compleasm
[pub-rb3]: https://pubmed.ncbi.nlm.nih.gov/39607778/
[sw-rb3]: https://github.com/lh3/ropebwt3
[sw-immuannot]: https://github.com/YingZhou001/Immuannot
[pub-immuannot]: https://pubmed.ncbi.nlm.nih.gov/38839374/
[sw-srf]: https://github.com/lh3/srf
[sw-mg]: https://github.com/lh3/minigraph
[pub-srf]: https://pubmed.ncbi.nlm.nih.gov/37918962/
[pub-rb2]: https://pubmed.ncbi.nlm.nih.gov/25107872/
[pub-gwfa]: https://arxiv.org/abs/2206.13574
[sw-gwfa]: https://github.com/lh3/gwfa

* [minipileup][sw-miniplp]: simple pileup-based variant caller, unpublished
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/minipileup"/>
  <a href="https://bioconda.github.io/recipes/minipileup/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/minipileup.svg?style=flag&label=Bioconda"/></a>
* [seqtk][sw-seqtk]: a small toolkit for manipulating sequences in FASTA/FASTQ, unpublished
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/seqtk"/>
  <a href="https://bioconda.github.io/recipes/seqtk/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/seqtk.svg?style=flag&label=Bioconda"/></a>
* [gfatools][sw-gfatools]: a toolkit for working with graphs in the GFA format, unpublished
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/gfatools"/>
  <a href="https://bioconda.github.io/recipes/gfatools/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/gfatools.svg?style=flag&label=Bioconda"/></a>
* [miniwfa][sw-miniwfa]: a reimplementation of the wavefront alignment algorithm at low memory. Unpublished but used in minigraph.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/miniwfa"/>
* [jstreeview][sw-jstv]: interactive phylogenetic tree viewer/editor in JavaScript, unpublished
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/jstreeview"/>

[sw-jstv]: https://github.com/lh3/jstreeview
[sw-miniplp]: https://github.com/lh3/minipileup
[sw-miniwfa]: https://github.com/lh3/miniwfa
[sw-gfatools]: https://github.com/lh3/gfatools
[sw-seqtk]: https://github.com/lh3/seqtk

#### Developed by past members or maintained by others

* [ntsm][sw-ntsm]: detecting sample swaps, published in [Chu and Li (2024)][pub-ntsm].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/JustinChu/ntsm"/>
  <a href="https://bioconda.github.io/recipes/ntsm/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/ntsm.svg?style=flag&label=Bioconda"/></a>
* [hifiasm][sw-hifiasm]: genome assembly with PacBio HiFi, Nanopore and Hi-C data,
  published in [Cheng et al (2021)][pub-ha1], [Cheng et al (2022)][pub-ha2] and [Cheng et al (2024)][pub-ha3].
  Maintained by Haoyu Cheng.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/chhylp123/hifiasm"/>
  <a href="https://bioconda.github.io/recipes/hifiasm/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/hifiasm.svg?style=flag&label=Bioconda"/></a>
* [hifiasm-meta][sw-hameta]: metagenome assembly with PacBio HiFi,
  published in [Feng et al (2022)][pub-hm1] and [Feng et al (2024)][pub-hm2].
  Maintained by Xiaowen Feng.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/xfengnefx/hifiasm-meta"/>
  <a href="https://bioconda.github.io/recipes/hifiasm_meta/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/hifiasm_meta.svg?style=flag&label=Bioconda"/></a>
* [T1K][sw-t1k]: HLA and KIR genotyping with short reads, published in [Song et al (2023)][pub-t1k].
  Maintained by Li Song.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/mourisl/T1K"/>
  <a href="https://bioconda.github.io/recipes/t1k/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/t1k.svg?style=flag&label=Bioconda"/></a>
* [chromap][sw-chromap]: aligning short ChIP-seq, ATAC-seq or Hi-C reads, published in [Zhang et al (2021)][pub-chromap].
  Maintained by Haowen Zhang and Li Song.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/haowenz/chromap"/>
  <a href="https://bioconda.github.io/recipes/chromap/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/chromap.svg?style=flag&label=Bioconda"/></a>
* [hifieval][sw-hifieval]: evaluating error correction accuracy for HiFi data, published in [Guo et al (2023)][pub-hifieval].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/magspho/hifieval"/>
  <a href="https://bioconda.github.io/recipes/hifieval/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/hifieval.svg?style=flag&label=Bioconda"/></a>
* [tabix][sw-tabix]: indexing and querying coordinate-sorted formats such as VCF and BED,
  published in [Li (2011)][pub-tabix].
  Now part of the samtools project.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/samtools/tabix"/>
  <a href="https://bioconda.github.io/recipes/tabix/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/tabix.svg?style=flag&label=Bioconda"/></a>
* [samtools][sw-samtools]: utilities for manipulating alignments in the SAM format.
  Initially published in [Li et al (2009)][pub-samtools1], [Li (2011a)][pub-samtools2] and [Li (2011b)][pub-samtools3].
  Maintained by Sanger since 2013.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/samtools/samtools"/>
  <a href="https://bioconda.github.io/recipes/samtools/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/samtools.svg?style=flag&label=Bioconda"/></a>
  <a href="https://bioconda.github.io/recipes/bcftools/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/bcftools.svg?style=flag&label=bcftools"/></a>
  <a href="https://bioconda.github.io/recipes/htslib/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/htslib.svg?style=flag&label=htslib"/></a>
* [TreeBeST][sw-treebest]: the core engine behind TreeFam for tree building.
  Some components are described in [PI's thesis][pub-thesis].
  Maintained by Ensembl Compara.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/Ensembl/treebest"/>
  <a href="https://bioconda.github.io/recipes/treebest/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/treebest.svg?style=flag&label=Bioconda"/></a>

[pub-hifieval]: https://pubmed.ncbi.nlm.nih.gov/37851384/
[sw-hifieval]: https://github.com/magspho/hifieval
[pub-ntsm]: https://pubmed.ncbi.nlm.nih.gov/38832466/
[sw-ntsm]: https://github.com/JustinChu/ntsm
[sw-chromap]: https://github.com/haowenz/chromap
[pub-chromap]: https://pubmed.ncbi.nlm.nih.gov/34772935/
[pub-t1k]: https://pubmed.ncbi.nlm.nih.gov/37169596/
[sw-t1k]: https://github.com/mourisl/T1K
[sw-samtools]: https://github.com/samtools/samtools
[sw-tabix]: https://github.com/samtools/tabix
[pub-tabix]: https://pubmed.ncbi.nlm.nih.gov/21208982/
[pub-samtools1]: https://pubmed.ncbi.nlm.nih.gov/19505943/
[pub-samtools2]: https://pubmed.ncbi.nlm.nih.gov/21320865/
[pub-samtools3]: https://pubmed.ncbi.nlm.nih.gov/21903627/
[sw-hifiasm]: https://github.com/chhylp123/hifiasm
[sw-hameta]: https://github.com/xfengnefx/hifiasm-meta
[pub-ha1]: https://pubmed.ncbi.nlm.nih.gov/33526886/
[pub-ha2]: https://pubmed.ncbi.nlm.nih.gov/35332338/
[pub-ha3]: https://pubmed.ncbi.nlm.nih.gov/38730258/
[pub-hm1]: https://pubmed.ncbi.nlm.nih.gov/35534630/
[pub-hm2]: https://pubmed.ncbi.nlm.nih.gov/38605401/

#### Old but functional

* [dna-nn][sw-dna-nn]: model and predict short DNA sequence features with neural networks, published in [Li (2019)][pub-dna-nn].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/dna-nn"/>
  <a href="https://bioconda.github.io/recipes/dna-nn/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/dna-nn.svg?style=flag&label=Bioconda"/></a>
* [hickit][sw-hickit]: 3D modeling for single-cell Hi-C, developed for [Tan et al (2018)][pub-hickit].
  It was not used in this paper but used in Longzhi Tan's later work.
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/hickit"/>
* [BGT][sw-bgt]: fast and lightweight genotype query across many samples, published in [Li (2016)][pub-bgt].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/bgt"/>
  <a href="https://bioconda.github.io/recipes/bgt/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/bgt.svg?style=flag&label=Bioconda"/></a>
* [fermi][sw-fermi], [fermi2][sw-fermi2] and [FermiKit][sw-fermikit]: short-read assembler,
  published in [Li (2012)][pub-fm1] and [Li (2015)][pub-fm2].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/fermi"/>
  <a href="https://bioconda.github.io/recipes/fermi/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/fermi.svg?style=flag&label=Bioconda"/></a>
* [fermi-lite][sw-fmlite]: a library in C for short-read assembly in small regions, adapted from FermiKit
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/fermi-lite"/>
  <a href="https://bioconda.github.io/recipes/fermi-lite/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/fermi-lite.svg?style=flag&label=Bioconda"/></a>
* [BFC][sw-bfc]: correcting sequencing errors in short reads, published in [Li (2015)][pub-bfc].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/bfc"/>
  <a href="https://bioconda.github.io/recipes/bfc/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/bfc.svg?style=flag&label=Bioconda"/></a>
* [bioawk][sw-bioawk]: BWK awk modified for biological data, unpublished
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/bioawk"/>
  <a href="https://bioconda.github.io/recipes/bioawk/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/bioawk.svg?style=flag&label=Bioconda"/></a>
* [psmc][sw-psmc]: infer historical population sizes from a diploid genome, published in [Li and Durbin (2011)][pub-psmc].
  <img style="margin: 0px" src="https://img.shields.io/github/stars/lh3/psmc"/>
  <a href="https://bioconda.github.io/recipes/psmc/README.html"><img style="margin: 0px" src="https://img.shields.io/conda/dn/bioconda/psmc.svg?style=flag&label=Bioconda"/></a>

[pub-dna-nn]: https://pubmed.ncbi.nlm.nih.gov/30989183/
[sw-dna-nn]: https://github.com/lh3/dna-nn
[pub-hickit]: https://pubmed.ncbi.nlm.nih.gov/30166492/
[sw-hickit]: https://github.com/lh3/hickit
[pub-bgt]: https://pubmed.ncbi.nlm.nih.gov/26500154/
[sw-bgt]: https://github.com/lh3/bgt
[sw-fmlite]: https://github.com/lh3/fermi-lite
[sw-bfc]: https://github.com/lh3/bfc
[pub-bfc]: https://pubmed.ncbi.nlm.nih.gov/25953801/
[pub-fm1]: https://pubmed.ncbi.nlm.nih.gov/22569178/
[pub-fm2]: https://pubmed.ncbi.nlm.nih.gov/26220959/
[sw-fermi]: https://github.com/lh3/fermi
[sw-fermi2]: https://github.com/lh3/fermi2
[sw-fermikit]: https://github.com/lh3/fermikit
[sw-bioawk]: https://github.com/lh3/bioawk
[sw-psmc]: https://github.com/lh3/psmc
[pub-psmc]: https://pubmed.ncbi.nlm.nih.gov/21753753/

#### Graveyard

* [MAQ][sw-maq]: short-read aligner, published in [Li et al (2008)][pub-maq].
  It is still working but there is no point to use it now.

[sw-maq]: https://maq.sourceforge.net
[pub-maq]: https://pubmed.ncbi.nlm.nih.gov/18714091/

### Resources

#### Updated resources since publication

* [Ropebwt3 index for human](https://zenodo.org/records/13948741), initially published in [Li (2024)][pub-rb3]. Also available [at AWS](https://openhgl.s3.us-east-1.amazonaws.com/index.html).
* [Ropebwt3 index for bacteria](https://zenodo.org/records/11533210)
* [Pangene graphs](https://zenodo.org/records/8118576), initially published in [Li et al (2024)][pub-pangene].
* [Minigraph graphs](https://zenodo.org/records/6286521), initially published in [Li et al (2020)][pub-minigraph].
* [Immuannot annotations](https://zenodo.org/records/8372991), initially published in [Zhou et al (2024)][pub-immuannot].
* [Easy genomic regions](https://zenodo.org/records/14903542) for short-read variant calling, published in [Li (2025)][pub-easy].
* [Pantree VCFs](https://zenodo.org/records/15374896) generated from HPRC graphs, preprinted in [Salehi Nowbandegani et al (2025)][pub-pantree].

#### Unpublished resources

* [Notable genomic regions](https://zenodo.org/records/10903864) in T2T-CHM13 and GRCh38.
* [Portable binaries](https://zenodo.org/records/5731012) for samtools v1.14 and for GCC v10.3.0 on CentOS 7.
* [Human reference genome analysis sets](https://zenodo.org/records/8045373) including BWA and Bowtie2 indices.
* [Haplotype-resolved PGP1 assembly](https://zenodo.org/records/5150756)

#### Graveyard

* [TreeFam][web-treefam]: database of animal gene trees.
  Published in [Li et al (2006)][pub-treefam1] and [Ruan et al (2008)][pub-treefam2],
  and described in [PI's thesis][pub-thesis].
  No longer maintained since 2013.

[pub-pangene]: https://pubmed.ncbi.nlm.nih.gov/39041615/
[sw-pangene]: https://github.com/lh3/pangene
[pub-minigraph]: https://pubmed.ncbi.nlm.nih.gov/33066802/
[web-treefam]: http://www.treefam.org
[pub-treefam1]: https://pubmed.ncbi.nlm.nih.gov/16381935/
[pub-treefam2]: https://pubmed.ncbi.nlm.nih.gov/18056084/
[pub-thesis]: https://github.com/lh3/thesis
[sw-treebest]: https://github.com/Ensembl/treebest
[pub-easy]: https://pubmed.ncbi.nlm.nih.gov/40905373/
[pub-pantree]: https://www.biorxiv.org/content/10.1101/2025.08.04.668502v1
