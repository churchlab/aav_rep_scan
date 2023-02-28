# aav_rep_scan
Contains code used to generate oligonucleotides for AAV2 rep scanning saturation mutagenesis library and to analyze resulting NGS data. Also includes code used to generate all figures in "Comprehensive mutagenesis maps the effect of all single codon mutations in the AAV2 rep gene on AAV production".

To get started, make a virtual environment using the provided requirements.txt file. You should then be able to lauch a Jupyter Notebook and run all library design and analysis code as provide.

````
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
````

The code to extract barcode sequences from the FASTQ files will require you to download all FASTQ files from [GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE226265).
