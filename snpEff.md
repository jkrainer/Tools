# snpEff
## Install and download database

```conda install -c bioconda snpeff ```

```java -jar snpEff.jar databases | grep GRCh38```

--> chose most recent database

```snpEff download GRCh38.99 -v```

## run snpEff

```snpEff -Xmx128g GRCh38.99 filtered.vcf > filtered.ann.vcf```

--> increase memory to -Xmx128g otherwise it crashes!
