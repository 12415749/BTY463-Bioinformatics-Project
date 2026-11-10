# BTY463 Bioinformatics Project

A reproducible bioinformatics pipeline on Kaggle for Oxford Nanopore sequencing analysis. It automates environment verification, directory setup, Dorado basecalling (v2.1.1), SLOW5/BLOW5 conversion via blue-crab (v0.5.0), and downstream processing on GPU.

## Project Structure
- `basecalling/`: Raw POD5/FAST5 basecalling scripts and outputs
- `alignment/`: Sequence alignment and mapping
- `variants/`: Variant calling analysis
- `qc/`: Quality control metrics
- `results/`: Processed figures and tables
