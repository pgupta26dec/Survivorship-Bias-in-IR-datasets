# Survivorship-Bias-in-IR-datasets

The project works on two main objectives. First is to analyse the msmarco-qna dataset with the intent of finding out patterns in answered and unanswered queries. Second is to find the extent to which survivorship bias can affect the sparsely labelled representativa dataset : MS MARCO.

## Datasets involved
Two msmarco datasets are used in this project: msmarco-qna (used mainly for analysis of data to gain understanding of queries) and the msmarco-passage(used for the reranking of the passages.)

## Running the notebook
The notebook "Survivorship_bias_in_MSMARCO" contains all the code that is written to pursue the objectives of the project. Due to the usage of google.colab imports, it is advised that the code is run on google colab. Another consideration is to have sufficient RAM which is essential to run the code.

## Downloading the data at runtime
The project deals with MS MARCO, which is a large dataset. During the tenure of the project, a copy of the MS MARCO was saved onto the google drive which helped in accelerating the process by bypassing the download of data at runtime. However, linking to the google drive requires user authentication. If the code is run withour linking it to the drive, the msmarco dataset would be downloaded at runtime using the ir_datasets python  package, which can be time-consuming because of the size of the dataset. The reranking results are fetched at runtime using the !wget command.


