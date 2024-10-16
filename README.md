# Bitcoin Heist Ransomware Address Dataset Project

This project uses the **BitcoinHeistRansomwareAddressDataset** from UCI to classify Bitcoin addresses associated with ransomware attacks. The goal is to build and evaluate models to classify addresses as either "white" (not linked to ransomware) or as specific malware-related addresses.

## Author
**Nima Shafiei Rezvani Nezhad**  
Email: nima.shafieirezvani@studio.unibo.it

## Dataset
- [BitcoinHeistRansomwareAddressDataset - UCI](https://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset)
- The dataset contains 665,173 rows and 10 columns: `address`, `year`, `day`, `length`, `weight`, `count`, `looped`, `neighbors`, `income`, `label`.

## Requirements

To install the required libraries, run:

```bash
pip install pyspark findspark
