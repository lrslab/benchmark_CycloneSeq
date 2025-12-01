# Introduction

Open Repository of Scripts and Resources for CycloneSEQ (CS1 and CS2) and Oxford Nanopore Technologies (R9.4.1 and R10.4.1) benchmarking.





# Quick links

## Scripts and pipeline

### Genetics

The [Giraffe](https://giraffe-documentation.readthedocs.io/en/latest/) documentation for read quality assessment. 

The [Flye](https://github.com/mikolmogorov/Flye/blob/flye/docs/USAGE.md) usage for bacterial genome assembly and [Racon](https://github.com/lbcb-sci/racon) usage for both long- and short-read polishing.

The [BUSCO](https://busco.ezlab.org/) introduction for genome completeness assessment.

The [QUAST](https://github.com/ablab/quast) introduction for mismatches among assemblies.





### Epigenetics

The [Hammerhead](https://hammerhead-documentation.readthedocs.io/en/latest/#) documentation for *de novo* bacterial methylation detection by stand-specific errors.

The adapted [Bonito](https://github.com/Runsheng/bonito) software for CycloneSEQ reads move table generation.

The [NanoCurEA](https://github.com/lrslab/CurEA) software for CycloneSEQ reads event generation.

The [NanoCEM](https://github.com/lrslab/nanoCEM) software for nanopore current signal comparison visualization.





## Results 

All the files can be found on [figshare](https://figshare.com/projects/Benchmarking_between_CycloneSEQ_and_ONT/267827).

Observed read accuracy tables are available [here](https://figshare.com/articles/dataset/Observed_read_accuracy_from_Giraffe_/30565385).

Estimated read accuracy tables are available [here](https://figshare.com/articles/dataset/Estimated_read_accuracy_from_Giraffe_/30565379).

Genome assemblies (WGS CS1 with NGS polishing）are available [here](https://figshare.com/articles/dataset/CS1_WGS_assemblies_with_NGS_polishing_/30548447).

Genome assemblies（WGS CS1 without NGS polishing）are available [here](https://figshare.com/articles/dataset/CS1_WGS_assemblies_without_NGS_polishing_/30548558).

Genome assemblies（WGS CS2 with NGS polishing）are available [here](https://figshare.com/articles/dataset/CS2_WGS_assemblies_with_NGS_polishing_/30565229).

Genome assemblies（WGS CS2 without NGS polishing）are available [here](https://figshare.com/articles/dataset/CS2_WGS_assemblies_without_NGS_polishing_/30565277).

Genome assemblies (WGA CS1 with NGS polishing）are available [here](https://figshare.com/articles/dataset/CS1_WGA_assemblies_with_NGS_polishing_/30548321).

Genome assemblies（WGA CS1 without NGS polishing）are available [here](https://figshare.com/articles/dataset/CS1_WGA_assemblies_without_NGS_polishing_/30548180).

Genome assemblies（WGA CS2 with NGS polishing）are available [here](https://figshare.com/articles/dataset/CS2_WGA_assemblies_with_NGS_polishing_/30565220).

Genome assemblies（WGA CS2 without NGS polishing）are available [here](https://figshare.com/articles/dataset/CS2_WGA_assemblies_without_NGS_polishing_/30565268).

The Quast results are available [here](https://figshare.com/articles/dataset/QUAST_results/30565664).

The Busco results are available [here](https://figshare.com/articles/dataset/BUSCO_results/30565661).

The MEME results (20 bp units enrichment) are available [here](https://figshare.com/articles/dataset/MEME_results_20_bp_units_/30565565).

The MEME results (30 bp units enrichment) are available [here](https://figshare.com/articles/dataset/MEME_results_30_bp_units_/30565568).





## Resource

- [Basecall model](https://figshare.com/account/projects/267827/articles/30744788) for CycloneSEQ reads, using Bonito. 
- All the FASTQ data is available [here](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA980403).
- The CycloneSEQ raw current signal of E. coli plasmid is available [here](https://github.com/lrslab/cyclone_plasmid_DNA/releases/tag/cyclone_data).



# Taxonomy

| Kingdom   |     Phylum     |        Class        |      Order       |       Family       |     Genus      |         Species          |
| -------- | :------------: | :-----------------: | :--------------: | :----------------: | :------------: | :----------------------: |
| Bacteria | Proteobacteria | Gammaproteobacteria | Pseudomonadales  |   Moraxellaceae    | Acinetobacter  |  *Acinetobacter pittii*  |
| Bacteria | Proteobacteria | Gammaproteobacteria | Enterobacterales | Enterobacteriaceae |  Escherichia   |    *Escherichia coli*    |
| Bacteria | Proteobacteria | Gammaproteobacteria | Enterobacterales | Enterobacteriaceae |   Klebsiella   | *Klebsiella pneumoniae*  |
| Bacteria | Proteobacteria | Gammaproteobacteria | Pseudomonadales  |  Pseudomonadaceae  |  Pseudomonas   | *Pseudomonas aeruginosa* |
| Bacteria | Proteobacteria | Gammaproteobacteria | Enterobacterales | Enterobacteriaceae |   Salmonella   |  *Salmonella enterica*   |
| Bacteria |   Firmicutes   |       Bacilli       | Lactobacillales  |  Enterococcaceae   |  Enterococcus  |  *Enterococcus faecium*  |



