# Baseline Human Antibody Repertoire Project

This repository contains code and data used for analysis of the baseline human antibody repertoire. Briefly, we performed
ultra-deep sequencing of the antibody repertoires of 10 healthy, adult subjects (approxmately 3 billion total antibody sequences). This sequencing revealed a massively diverse antibody repertoire with surprisingly high overlap between the repertoires of different subjects.

## Code
The code used in this project is assembled into a series of Juypter notecooks. There are two sets of notebooks, those containing code used for [DATA PROCESSING](https://github.com/briney/grp_paper/tree/master/data_processing) and those containing code used to [MAKE FIGURES](https://github.com/briney/grp_paper/tree/master/make_figures). GitHub will render each of the notebooks, but the code cannot be executed from within GitHub. If you'd like to actually run the code contained in the notebooks, you must clone the repository.

**_NOTE:_** *Whenever possible, the intermediate datasets required to run the code are included in this repository, however, many intermediate datasets are too large to be included. In such cases, links to the required datasets are provided in the appropriate notebook.*

## Datasets  
Raw and processed datasets from each subject can be downloaded using the following links:

  - 316188: [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/316188_HNCHNBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/316188_HNCHNBCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- [**Annotated CSVs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/316188_HNCHNBCXY_consensus_UID18-cdr3nt-90_minimal_071817.tar.gz) -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/316188_HNCHNBCXY_consensus_UID18-cdr3nt-90_json_071817.tar.gz)
  - 326650:  [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326650_HCGCYBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326650_HCGCYBCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- [**Annotated CSVs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326650_HCGCYBCXY_consensus_UID18-cdr3nt-90_minimal_071817.tar.gz) -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326650_HCGCYBCXY_consensus_UID18-cdr3nt-90_json_071817.tar.gz)
  - 326651:  [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326651_HC5LVBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326651_HC5LVBCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- **Annotated CSVs** -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326651_HC5LVBCXY_consensus_UID18-cdr3nt-90_jsons_071817.tar.gz)
  - 326713:  [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326713_HJLLNBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326713_HJLLNBCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- **Annotated CSVs** -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326713_HJLLNBCXY_consensus_UID18-cdr3nt-90_jsons_071817.tar.gz)
  - 326737:  [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326737_HNKVKBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326737_HNKVKBCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- [**Annotated CSVs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326737_HNKVKBCXY_consensus_UID18-cdr3nt-90_minimal_071817.tar.gz) -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326737_HNKVKBCXY_consensus_UID18-cdr3nt-90_json_071817.tar.gz)
  - 326780:  [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326780_HLH7KBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326780_HLH7KBCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- [**Annotated CSVs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326780_HLH7KBCXY_consensus_UID18-cdr3nt-90_minimal_071817.tar.gz) -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326780_HLH7KBCXY_consensus_UID18-cdr3nt-90_json_071817.tar.gz)
  - 326797:  [**FASTQs_1**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326780_HLH7KBCXY_raw-fastqs.tar.gz) [**FASTQs_2**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326797_HCGNLBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326797_HCGNLBCXY%2BHJLN5BCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- [**Annotated CSVs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326797_HCGNLBCXY%2BHJLN5BCXY_consensus_UID18-cdr3nt-90_minimal_071817.tar.gz) -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326797_HCGNLBCXY%2BHJLN5BCXY_consensus_UID18-cdr3nt-90_json_071817.tar.gz)
  - 326907:  [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326907_HLT33BCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326907_HLT33BCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- [**Annotated CSVs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326907_HLT33BCXY_consensus_UID18-cdr3nt-90_minimal_071817.tar.gz) -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/326907_HLT33BCXY_consensus_UID18-cdr3nt-90_json_071817.tar.gz)
  - 327059:  [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/327059_HCGTCBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/327059_HCGTCBCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- [**Annotated CSVs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/327059_HCGTCBCXY_consensus_UID18-cdr3nt-90_minimal_071817.tar.gz) -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/327059_HCGTCBCXY_consensus_UID18-cdr3nt-90_json_071817.tar.gz)
  - D103:  [**FASTQs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/D103_HCGCLBCXY_raw-fastqs.tar.gz) -- [**UMI-corected consensus FASTAs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/D103_HCGCLBCXY_consensus_UID18-cdr3nt-90_071817.tar.gz) -- [**Annotated CSVs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/D103_HCGCLBCXY_consensus_UID18-cdr3nt-90_minimal_071817.tar.gz) -- [**Annotated JSONs**](http://burtonlab.s3.amazonaws.com/sequencing-data/hiseq_2016-supplement/D103_HCGCLBCXY_consensus_UID18-cdr3nt-90_json_071817.tar.gz)

For each subject, there are a total of 18 samples: 3 technical replicates of each of 6 biological replicates. Biological replicates refer to different aliquots of peripheral blood monomuclear cells (**PBMCs**), from which total RNA was separately isolated and processed. Thus, sequences or clonotypes found in multiple biological replicates are assumed to have independently occurred in different cells. Technical relicates refer to independent library preparations using the same aliquot of PBMC-derived RNA. In each of the above datasets, samples 1-6 are biological replicates. Samples 7-12 and 13-18 are technical replicates of samples 1-6.

Due to technical issues, the sequence data for subject 326797 was spread across two HiSeq flowcells. Thus, the raw FASTQs may be downloaded in two separate batches. Starting with the first processed dataset (UMI-corrected consensus FASTAs), reads from both flowcells were pooled.

## Requirements

  - Python 3.3+ (although Python 2.7 may work for many or most notebooks, this has not been tested)
  - [Jupyter Notebook](https://jupyter.org/install)

*Additionally, each notebook may require additional third-party Python packages. Any notebook-specific requirements, as well as instructions for package installation with [pip](https://pip.pypa.io/en/stable/installing/), are provided in each notebook.*

If you're new to Python, a great way to get started is to install the [Anaconda Python distribution](https://www.continuum.io/downloads), which includes pip as well as a ton of useful scientific Python packages.

