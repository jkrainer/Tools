**Group comparison**

`plink -assoc --file freebayes_Q100_DP10_NS2_snpeff_dbsnp_PLINK --pheno phenofile_name.txt --double-id --allow-extra-chr --all-pheno --allow-no-sex -pfilter 0.05`

**Annotate Plink output file with gene names (bed file)**

`plink --annotate plink.GROUP.qassoc ranges=/home/epityp/reference/ensembl_ref_genome/gene_list_hg38.bed --out PREFIX`
