# FragileX-FMR1-Mutation-Lab

## Student
Estrellanes, Klea Mae G.

## Disease
Fragile X Syndrome

## Gene
FMR1 — Fragile X Messenger Ribonucleoprotein 1

## Reference Sequence
- Transcript: NM_002024.6
- Protein: NP_002015.1
- CDS length: 1,899 bp
- Protein length: 632 aa

## Documented Mutation
- Variant: NM_002024.6:c.80C>A
- Protein change: p.Ser27Ter
- Mutation type: Nonsense single-nucleotide substitution
- ClinVar Variation ID: 29987
- ClinVar accession: VCV000029987.1
- Clinical interpretation: Pathogenic

## Artificial Mutation
- Mutation: 3-bp deletion of GGC
- Protein change: p.Gly10del
- Mutation type: In-frame deletion

## Tools Used
- NCBI RefSeq
- NCBI ClinVar
- Galaxy
- EMBOSS transeq
- EMBOSS Needle

## Galaxy History
Estrellanes_FragileX_FMR1_Mutation_Lab

## Repository Structure
- `01_reference/` — WT CDS and protein
- `02_documented_mutation/` — documented mutant CDS and protein
- `03_artificial_mutation/` — artificial mutant CDS and protein
- `04_results/` — Needle alignment and result summary
- `05_report/` — final report files

## Summary
This project investigated how a documented FMR1 nonsense mutation affects the predicted FMRP protein. The c.80C>A substitution changes codon 27 from TCA to TAA, producing the nonsense variant p.Ser27Ter and a premature stop codon. An artificial three-base-pair deletion was also analyzed to compare the effects of an in-frame deletion with a nonsense mutation.
