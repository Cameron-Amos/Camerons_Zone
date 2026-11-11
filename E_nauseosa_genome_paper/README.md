

### Genotype Matrix:
--structure (in Stacks)

### PCA:
plink, LD prune optionally if haven't

### ENTROPY:
Get ancestry proportions (green/gray, or green/gray/desert) from each individual

### UMAP:
bcftools to filter everything noramlly, cull bialleleic (do depth filtering, MAF, excessive missingness, snp missingness)
pipe into python script the completed vcf and use umap to generate plot, use in compliment to PCA not as a replacement. Tom also says there's an R package.

### EEMRS:
Already have workflow, see pop structure and historic gene flow across geography

### SVDQuartets:
Create phylogenetic trees to uncover evolutionary relationship, codes in PAUP* which i've never used before
