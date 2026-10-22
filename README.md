# Cameron Amos PhD work organizational framework

This repository is meant to organize thoughts, priorities, project flow, and code for projects and peripheral work for Cam's dissertation research.

Directories contain X, Y, Z

## Spring 2026 things to think and talk about


## Specific projects, and ideas for projects

- we want to emphasize synergy/opportunity for collaboration with Bryce
- landscollective

## Common Garden Radseq
Seeking to build up a high quality set of data for the ERNA common gardens, for downstream studies of pop gen, comparative genetics, as well as phenological data and GxE interactions. We're shooting for at least 15x coverage, from two p4 lanes. If we successfully receive a CORE award we can get one kit, which would generate half of the needed data. If not, we will do it entirely though another company (Edenborough Genetics?)

### In Hand

- Old Rabbitbrush data from Trevor (nonhybrids)
- Should we look at the entire set at all? Perhaps everything together in the end.

### Actions to be Taken

1- Avoid Angsd, use stacks instead. Create a pipeline with the works: Variant calling (Tom likes using Entropy), filtering. How are we using vcftools? What kind of data matrix are we getting out of Trevors data, how many loci? Are we bing too strict?
2- Get genotype matrix and for struct, pca, umap, eems, everything squared away.

To obtain the data:

1- (DONE) Allow FS money to arrive at UNR 
2- Collect samples from Central Ferry, and ship on dry ice to UNR. 
3- Library prep will be done, likely by Tom. If Core Award is not obtained, all samples will be sent to a 3rd party company for size selection and sequencing. Otherwise, half of it will be done here in the university through the UNR Genomics Core with Andrew.
4- Once data is received, execute entire pipeline on the data.
5- Goal is to indentify with PCAs and UMAP the MOST confident green/consimilis individual as a representative for the new E. nauseosa reference genome (green/consimilis).


### Deliverables
- The identification of a single consimilis/green individual which will be used as the sample for WGS for an additional rabbitbrush reference genome
- Creation of a genotype matrix which can be used for downstream Genetic Environment Association studies, GxE interactions of common garden, even forward genetic studies utilizing GWAS to find the source of traits, etc...


## E. nauseosa ssp. consimilis reference genome (green)
Currently waiting on radseq data in order to identify an individual that is squarely, nonhybrid consimilis.

### In Hand

- The previous Rabbitbrush genome (E. nauseosa ssp. nauseosa, 'gray'), as well as it's annotation data. 

### Actions to be taken

Candidate Identification
1- Execute entire pipeline on the new radseq data.
2- Identify with PCAs and UMAP the MOST confident green/consimilis individual as a representative for the new E. nauseosa reference genome (green/consimilis).

Whole Genome Sequencing
3- Harvest the sample in Central Ferry common garden that corresponds to the ID of the highest confidence individual, and prepare on dry ice
4- Ship to Eidenborough genetics for WGS if there is nothing needed to be done at UNR first.

Downstream Analysis
5- Compare two reference genomes
6- Map all samples onto both and see how they both compare
7- Much more...

### Deliverables
A new high-depth reference genome which may be used to identify inversions between the two rabbitbrush subspecies, or bring other insights into the common garden data. 


## Chaenactis douglasii Project

### In Hand

- All of Caro's data which she previously worked on:
  - HTML: https://nevada-my.sharepoint.com/shared?listurl=https%3A%2F%2Fnevada%2Dmy%2Esharepoint%2Ecom%2Fpersonal%2Ftparchman%5Funr%5Fedu%2FDocuments&id=%2Fpersonal%2Ftparchman%5Funr%5Fedu%2FDocuments%2FAttachments%2Fchdo%2Ehtml&parent=%2Fpersonal%2Ftparchman%5Funr%5Fedu%2FDocuments%2FAttachments&shareLink=1&ga=1
  - Figures: https://nevada-my.sharepoint.com/:u:/g/personal/tparchman_unr_edu/IQDX5bRkreRtS6Sa5Ims3QG3AXFt893wzTIFHCg4IfukLnc
- 350ish samples of single-end fastqs, only some of which we have ploidy information for
- Master copy of CHDO I used for previous analysis
- CHDO plate data Bryce sent
- [[MISSING]] is the plate barcodes for the CHDO data, which would allow us to identify the populations and lat/long of the two-letter codes of the fastqs.

### Actions to be taken

1- Find plate barcodes for CHDO data
2- Make a new master dataframe of all current data with pop codes, pop names, lat,long, and genome size if we have it.
3- Identify which samples have ploidy data, and their geographic location
4- Consider if it is worth it to go on a collection road trip in order to obtain ploidy data for them. 
5- Construct denovo genome assembly with new data, 

### Deliverables
Several papers clarifying the genetic and geographic landscape of CHDO, as well as diagnostic zones which can be used to assume ploidy of a CHDO population which can inform future seed collections.

## Seed Processing 

## Assets/Links
Seth's Filtering Guide:
https://github.com/tparchman/lab/blob/master/FilteringGuide.md

Local_PCA (Diana's Timema)
https://github.com/zgompert/TimemaPolygenicSelection
https://github.com/dianatataru/Timema-SV-Methods/blob/main/README.md

Example Stacks GBS pipeline
https://github.com/duceppemo/GBS_stacks





