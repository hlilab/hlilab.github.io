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
We also explore a variety of algorithms related to variant calling (e.g. longcallR and dipcall),
gene annotation (e.g. Immuannot and compleasm),
pangenome analysis (e.g. minigraph and pangene),
full-text indexing (e.g. ropebwt3)
and evolution (e.g. psmc).
Most of our tools work years after their initial publications and are often well received.

### Software

#### Current

* [longcallD][sw-longcallD]: small and large variant calling from long genomic reads, unpublished
* [longcallR][sw-longcallR]: SNP calling and haplotype-specific analysis from long RNA-seq reads, unpublished
* [ropebwt3][sw-rb3]: construction and utility of BWT for DNA string sets, published in [Li (2014)][pub-rb2] and [Li (2024)][pub-rb3].
* [Immuannot][sw-immuannot]: annotating HLA and KIR genes in phased assemblies, published in [Zhou et al (2024)][pub-immuannot].
* [pangene][sw-pangene]: constructing a pangenome gene graph, published in [Li (2024)][pub-pangene].
* [compleasm][sw-minibusco]: a reimplementation of BUSCO for evaluating the gene completeness of an assembly, published in [Huang and Li (2023)][pub-minibusco].
* [srf][sw-srf]: assembling satellite DNA, published in [Zhang et al (2023)][pub-srf].
* [miniprot][sw-miniprot]: protein-to-genome alignment allowing splicing and frameshift, published in [Li (2023)][pub-miniprot].
* [bedtk][sw-bedtk] and [cgranges][sw-cgr]: a fast toolkit and library for working with BED files, published in [Li and Rong (2020)][pub-bedtk].
* [yak][sw-yak]: k-mer counting and assembly evaluation, developed for [Cheng et al (2021)][pub-ha1].
* [gwfa][sw-gwfa]: graph wavefront alignment with edit distance, published in [Zhang et al (2022)][pub-gwfa].
  Merged into gfatools and used by minigraph.
* [minigraph][sw-mg]: pangenome construction and sequence-to-graph alignment, published in [Li et al (2020)][pub-minigraph].
* [dipcall][sw-dipcall]: variant calling for phased diploid assemblies, developed for [Li et al (2019)][pub-dipcall].
* [minimap2][sw-minimap2]: widely used long-read aligner, published in [Li (2018)][pub-minimap2a] and improved in [Li (2021)][pub-minimap2b].
* [miniasm][sw-miniasm]: a simple long-read assembler, published in [Li (2016)][pub-miniasm].
  Useful for assembly at small scale; not recommended for production.
* [BWA][sw-bwa]: widely used short-read aligner,
  published in [Li and Durbin (2009)][pub-bwa1], [Li and Durbin (2010)][pub-bwa2] and [Li (2013)][pub-bwa3].

[sw-longcallD]: https://github.com/yangao07/longcallD
[sw-longcallR]: https://github.com/huangnengCSU/longcallR
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
* [seqtk][sw-seqtk]: a small toolkit for manipulating sequences in FASTA/FASTQ, unpublished
* [gfatools][sw-gfatools]: a toolkit for working with graphs in the GFA format, unpublished
* [miniwfa][sw-miniwfa]: a reimplementation of the wavefront alignment algorithm at low memory. Unpublished but used in minigraph.
* [jstreeview][sw-jstv]: interactive phylogenetic tree viewer/editor in JavaScript, unpublished

[sw-jstv]: https://github.com/lh3/jstreeview
[sw-miniplp]: https://github.com/lh3/minipileup
[sw-miniwfa]: https://github.com/lh3/miniwfa
[sw-gfatools]: https://github.com/lh3/gfatools
[sw-seqtk]: https://github.com/lh3/seqtk

#### Developed by past members or maintained by others

* [ntsm][sw-ntsm]: detecting sample swaps, published in [Chu and Li (2024)][pub-ntsm].
* [hifiasm][sw-hifiasm]: genome assembly with PacBio HiFi, Nanopore and Hi-C data,
  published in [Cheng et al (2021)][pub-ha1], [Cheng et al (2022)][pub-ha2] and [Cheng et al (2024)][pub-ha3].
  Maintained by Haoyu Cheng.
* [hifiasm-meta][sw-hameta]: metagenome assembly with PacBio HiFi,
  published in [Feng et al (2022)][pub-hm1] and [Feng et al (2024)][pub-hm2].
  Maintained by Xiaowen Feng.
* [T1K][sw-t1k]: HLA and KIR genotyping with short reads, published in [Song et al (2023)][pub-t1k].
  Maintained by Li Song.
* [chromap][sw-chromap]: aligning short ChIP-seq, ATAC-seq or Hi-C reads, published in [Zhang et al (2021)][pub-chromap].
  Maintained by Haowen Zhang and Li Song.
* [hifieval][sw-hifieval]: evaluating error correction accuracy for HiFi data, published in [Guo et al (2023)][pub-hifieval].
* [tabix][sw-tabix]: indexing and querying coordinate-sorted formats such as VCF and BED,
  published in [Li (2011)][pub-tabix].
  Now part of the samtools project.
* [samtools][sw-samtools]: utilities for manipulating alignments in the SAM format.
  Initially published in [Li et al (2009)][pub-samtools1], [Li (2011a)][pub-samtools2] and [Li (2011b)][pub-samtools3].
  Maintained by Sanger since 2013.
* [TreeBeST][sw-treebest]: the core engine behind TreeFam for tree building.
  Some components are described in [PI's thesis][pub-thesis].
  Maintained by Ensembl Compara.

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
* [hickit][sw-hickit]: 3D modeling for single-cell Hi-C, developed for [Tan et al (2018)][pub-hickit].
  It was not used in this paper but used in Longzhi Tan's later work.
* [BGT][sw-bgt]: fast and lightweight genotype query across many samples, published in [Li (2016)][pub-bgt].
* [fermi][sw-fermi], [fermi2][sw-fermi2] and [FermiKit][sw-fermikit]: short-read assembler,
  published in [Li (2012)][pub-fm1] and [Li (2015)][pub-fm2].
* [fermi-lite][sw-fmlite]: a library in C for short-read assembly in small regions, adapted from FermiKit
* [BFC][sw-bfc]: correcting sequencing errors in short reads, published in [Li (2015)][pub-bfc].
* [bioawk][sw-bioawk]: BWK awk modified for biological data, unpublished
* [psmc][sw-psmc]: infer historical population sizes from a diploid genome, published in [Li and Durbin (2011)][pub-psmc].

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

* Ropebwt3 indices [for human][res-rb3-human] and [for bacteria][res-rb3-bac],
  initially published in [Li (2024)][pub-rb3].
* [Pangene graphs][res-pangene], initially published in [Li et al (2024)][pub-pangene].
* [Minigraph graphs][res-minigraph], initially published in [Li et al (2020)][pub-minigraph].

#### Unpublished resources

* Manually curated [locations of centromeric repeats][res-cenloc] for variant filtering.
* [Human reference genome analysis sets][res-hg-idx] including BWA and Bowtie2 indices.
* [Portable binaries][res-portable-bin] for samtools v1.14 and for GCC v10.3.0 on CentOS 7.
* [Haplotype-resolved PGP1 assembly][res-pgp1]
* [Easy genomic regions for short-read variant calling][res-easy]

#### Graveyard

* [TreeFam][web-treefam]: database of animal gene trees.
  Published in [Li et al (2006)][pub-treefam1] and [Ruan et al (2008)][pub-treefam2],
  and described in [PI's thesis][pub-thesis].
  No longer maintained since 2013.

[res-easy]: https://zenodo.org/records/14903542
[res-pgp1]: https://zenodo.org/records/5150756
[res-rb3-human]: https://doi.org/10.5281/zenodo.13948741
[res-rb3-bac]: https://doi.org/10.5281/zenodo.11533210
[res-pangene]: https://doi.org/10.5281/zenodo.8118576
[pub-pangene]: https://pubmed.ncbi.nlm.nih.gov/39041615/
[sw-pangene]: https://github.com/lh3/pangene
[res-minigraph]: https://doi.org/10.5281/zenodo.6286521
[pub-minigraph]: https://pubmed.ncbi.nlm.nih.gov/33066802/
[res-cenloc]: https://doi.org/10.5281/zenodo.10903864
[res-hg-idx]: https://doi.org/10.5281/zenodo.8045373
[res-portable-bin]: https://doi.org/10.5281/zenodo.5731012
[web-treefam]: http://www.treefam.org
[pub-treefam1]: https://pubmed.ncbi.nlm.nih.gov/16381935/
[pub-treefam2]: https://pubmed.ncbi.nlm.nih.gov/18056084/
[pub-thesis]: https://github.com/lh3/thesis
[sw-treebest]: https://github.com/Ensembl/treebest
