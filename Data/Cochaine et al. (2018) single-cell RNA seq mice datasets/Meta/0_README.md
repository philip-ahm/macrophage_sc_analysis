### META DATA



<u>*Explanation*</u>:

*This file contains a full description of the data or refers to other documents in the meta-data directory that contains such description.*



*<u>Instructions</u>:* 

* *Remove all Instructions and the Explanation once you have completed the template.*
* *Level of detail: Information provided should be sufficient for someone who was not involved in the project and/or has limited knowledge about the topic,  to understand and reproduce the project.* 



*====== TEMPLATE STARTS HERE ======*



**Dataset 1:** Series GSE97310

* Who created the data (data owner): Antoine-Emmanuel Saliba

* License

  

* Description of samples (e.g., sample sheets):

**Sample GSM2561498**: 

Characteristics	strain/background: C57BL/6J
genotype/variation: Ldlr-/-
Sex: male
tissue: aorta
cell type: leukocytes
cell marker: CD45+
treatment: 20 weeks high fat, high cholesterol diet

**Sample GSM2882367**:

Characteristics	strain/background: C57BL/6J
genotype/variation: Ldlr-/-
Sex: male
tissue: aorta
cell type: leukocytes
cell marker: CD45+
treatment: 11 weeks high fat, high cholesterol diet

* Experimental design:

We sorted total viable CD45+ leukocytes from the aortas of male Ldlr-/- mice. Three samples were tested: control, after 11 and 20 weeks of a high fat, high cholesterol diet.
Chromium™ Controller was used for partitioning single cells into nanoliter-scale Gel Bead-In-EMulsions (GEMs) and Single Cell 3’ reagent kit v2 for reverse transcription, cDNA amplification and library construction (10x Genomics). The detailed protocol was provided by 10x Genomics.

* Content and format of the data files:

Data were analyzed using Cell Ranger™ v1.3 pipelines and were visualized by Loupe™ Cell Browser. Both are available in 10x Genomics website.
Genome_build: mm10 (GRCm38)
Supplementary_files_format_and_content: csv format: Files include mean UMI counts, log2 fold changes and adjusted p-values for the differentially expressed genes among the identified cell clusters.
Supplementary_files_format_and_content: h5 format: Contains the per molecule read information from Cell Ranger. The instructions to read the matrix in hdf5 format can be found here: https://support.10xgenomics.com/single-cell/software/pipelines/latest/advanced/h5_matrices

* Why the data were generated:

* How the data were generated (measurement platform) :

Instrument model	Illumina HiSeq 2500

* ........
