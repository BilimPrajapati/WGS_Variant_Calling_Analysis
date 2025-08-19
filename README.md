This repository contains a few files resulting from the analysis of whole-genome sequencing (WGS) data, including variant calling, filtering, and functional annotation.

The .tranches file generated during Variant Quality Score Recalibration (VQSR). This file summarizes variant quality tranches at different sensitivity thresholds, reporting key metrics such as the number of known and novel variants retained, Ti/Tv ratios, truth sensitivity, and the minimum VQSLOD cutoff score used.

The high_impact_variants.vcf file contains all high-impact variants identified and annotated using SnpEff, while high_impact_table.txt provides a simplified table with key fields (CHROM, POS, ID, REF, ALT, IMPACT, EFFECT, GENE) for easier interpretation.

