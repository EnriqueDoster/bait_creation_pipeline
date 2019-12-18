# Creating Mannheimia haemolytica sequencing baits
------------

Goal: Use the CATCH software to create sequencing baits for Mannheimia haemolytica
[CATCH](https://github.com/broadinstitute/catch)

Tasks:
  1. Run CATCH to create baits
    * Optimize with pipeline
    * Test various "design.py" flags
  2. Improve specificity of baits
    * Test kraken and/or blast to identify contaminant sequences



# Running pipeline
------------

### Example command
```bash
nextflow run main_bait_design.nf --reference_genome /home/enriquedoster/Documents/Projects/Mann_heim_69_genomes/genome_assemblies/ncbi-genomes-2019-08-28/GCF_007963885.1_ASM796388v1_genomic.fna --input_dir /home/enriquedoster/Documents/Projects/63_genomes/test_dir -profile singularity --output test_WGS
```



# Documents
------------

## Genome data
- [M. Clawson genomes](https://github.com/EnriqueDoster/bait_creation_pipeline/tree/master/docs/M_haemolytica_literature/Clawson_genome_data)
  * Figure 1 shows a tree of M. haemolytica isolates made in EDGAR.  There are two major genotypes and one deep branch of an outlier.
  * Figure 2 shows a tree of genotype 1 M. haemolytica isolates made in EDGAR with five subtypes previously described in the attached paper.
  * Figure 3 shows a tree of genotype 1 M. haemolytica isolates made in Parsnp/Gingr with the ICE region removed.
  * Figure 4 shows a tree of genotype 2 M. haemolytica made in EDGAR.  The four subtypes of genotype 2 were previously described in the attached paper.  The ICE region is included in this tree.
  * Figure 5 shows a tree of genotype 2 M. haemolytica made in Parsnp/Gingr with the ICE region removed.

 
## Antimicrobial resistance baits
- [MEGARich](https://github.com/EnriqueDoster/bait_creation_pipeline/blob/master/docs/M_haemolytica_literature/2017.Noyes%20MEGaRICH%20-Microbiome.pdf)

