---
title: "HLi Lab - Software"
layout: textlay
excerpt: "Software and Resources"
sitemap: false
permalink: /software
---

### Software

#### Developed by current members and functional

* [Minimap2][sw-minimap2]: widely used long-read aligner,
  published in [Li (2018)][pub-minimap2a] and [Li (2021)][pub-minimap2b].
* [BWA][sw-bwa]: widely used short-read aligner,
  published in [Li and Durbin (2009)][pub-bwa1], [Li and Durbin (2010)][pub-bwa2] and [Li (2013)][pub-bwa3].

#### Developed by past members or maintained by others

* [Tabix][sw-tabix]: indexing and querying coordinate-sorted formats such as VCF and BED.
  Published in [Li (2011)][pub-tabix].
  Now part of the samtools project.
* [Samtools][sw-samtools]: utilities for manipulating alignments in the SAM format.
  Initially published in [Li et al (2009)][pub-samtools1], [Li (2011a)][pub-samtools2] and [Li (2011b)][pub-samtools3].
  Maintained by Sanger since 2013.
* [TreeBeST][sw-treebest]: the core engine behind TreeFam for tree building.
  Some components are described in [PI's thesis][pub-thesis].
  Maintained by Ensembl Compara.

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

#### Dead

* [TreeFam][web-treefam]: database of animal gene trees.
  Published in [Li et al (2006)][pub-treefam1] and [Ruan et al (2008)][pub-treefam2],
  and described in [PI's thesis][pub-thesis].
  No longer maintained since 2013.

[res-rb3-human]: https://doi.org/10.5281/zenodo.13948741
[res-rb3-bac]: https://doi.org/10.5281/zenodo.11533210
[res-pangene]: https://doi.org/10.5281/zenodo.8118576
[pub-rb3]: https://pubmed.ncbi.nlm.nih.gov/39607778/
[pub-pangene]: https://pubmed.ncbi.nlm.nih.gov/39041615/
[res-minigraph]: https://doi.org/10.5281/zenodo.6286521
[pub-minigraph]: https://pubmed.ncbi.nlm.nih.gov/33066802/
[res-cenloc]: https://doi.org/10.5281/zenodo.10903864
[res-hg-idx]: https://doi.org/10.5281/zenodo.8045373
[res-portable-bin]: https://doi.org/10.5281/zenodo.5731012
[sw-samtools]: https://github.com/samtools/samtools
[pub-samtools1]: https://pubmed.ncbi.nlm.nih.gov/19505943/
[pub-samtools2]: https://pubmed.ncbi.nlm.nih.gov/21320865/
[pub-samtools3]: https://pubmed.ncbi.nlm.nih.gov/21903627/
[sw-tabix]: https://github.com/samtools/tabix
[pub-tabix]: https://pubmed.ncbi.nlm.nih.gov/21208982/
[web-treefam]: http://www.treefam.org
[pub-treefam1]: https://pubmed.ncbi.nlm.nih.gov/16381935/
[pub-treefam2]: https://pubmed.ncbi.nlm.nih.gov/18056084/
[pub-thesis]: https://github.com/lh3/thesis
[sw-treebest]: https://github.com/Ensembl/treebest
[sw-minimap2]: https://github.com/lh3/minimap2
[pub-minimap2a]: https://pubmed.ncbi.nlm.nih.gov/29750242/
[pub-minimap2b]: https://pubmed.ncbi.nlm.nih.gov/34623391/
[sw-bwa]: https://github.com/lh3/bwa
[pub-bwa1]: https://pubmed.ncbi.nlm.nih.gov/19451168/
[pub-bwa2]: https://pubmed.ncbi.nlm.nih.gov/20080505/
[pub-bwa3]: https://arxiv.org/abs/1303.3997
