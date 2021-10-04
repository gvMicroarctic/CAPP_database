# CAPP database

The Cold-Adapted Predicted Protein (CAPP) database is a database of predicted proteins. These proteins were annotated from a high-quality assembly recontructed from Nanopore and Illumina sequences from frozen soil microbial communities sampled in the Greenland Ice Sheet foreland in the proximity of Kangerlussuaq. The CAPP database accounts of 3,076,838 entries. For more information about the database please refer to Varliero et al. 2021 (https://doi.org/10.1093/femsec/fiab127).

### Cold-Adapted Predicted Proteins

The Cold-Adapted Predicted Proteins can be downloaded from https://www.cerealsdb.uk.net/CAPP/CAPP_db.faa.gz.

### Cold-Adapted Predicted Genes

The Cold-Adapted Predicted Genes can be downloaded from https://www.cerealsdb.uk.net/CAPP/CAPP_db.fasta.gz.

### General information associated to each CAPP entry

The General information associated to each CAPP entry can be downloaded from https://www.cerealsdb.uk.net/CAPP/CAPP_db.txt.gz. The txt file reports the following information:		

- CAPP entry : entry accession number reported in the CAPP database
- assignment : how the sequence was annotated; if by similarity to the UniProt database, or to a protein motif
- predicted_gene : gene name
- predicted_protein : protein name
- EC_number : EC number (https://enzyme.expasy.org)
- taxonomy : taxonomy associated to the CAPP entry; taxonomy was assigned using the LongMeta pipeline (https://github.com/gvMicroarctic/LongMeta)
- MAG : MAG associated to the CAPP entry; if the entry was not annotated from any MAG, this field's value is 'no'
- cDNA_match : this field is 'yes' if at least one cDNA read is associated to the CAPP entry; this field is 'no' if no cDNA reads were associated to the CAPP entry
- nr_dataset : nr sequences associated to the CAPP entry; if the entry was not similar to any nr sequence, this field value is 'no'

### Geochemical data associated to each CAPP entry

The geochemical data associated to each CAPP entry can be downloaded from https://www.cerealsdb.uk.net/CAPP/CAPP_db_geo.txt.gz. This file reports for each CAPP entry that was found expressed in the environmental samples (i.e. present in the cDNA libraries), the ranges of values associated to those samples for each of the measured geochemical variables. The txt file reports the following information:

- CAPP_entry : entry accession number reported in the CAPP database
- root_content (%)
- organic_content (%)
- soil_moisture_content (%)
- pH
- nitrate (ppm)
- ammonia (ppm)
- phosphate (ppm)
- sulphate (ppm)
- sodium (ppm)
- potassium (ppm)
- magnesium (ppm)
- calcium (ppm)
- iron (ppm)
- silica (ppm)
- TN (ppm)
- DON (ppm)
- TP (ppm)
- DOP (ppm)
- DOC (ppm)
