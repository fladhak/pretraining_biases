# When Do Pre-Training Biases Propagate to Downstream Tasks? A Case Study in Text Summarization

This repository contains the data for paper [When Do Pre-Training Biases Propagate to Downstream Tasks? A Case Study in Text Summarization](https://aclanthology.org/2023.eacl-main.234.pdf)

## Downlaod the data
All the data is contained is uploaded to a [gogole drive folder](https://drive.google.com/drive/folders/1r0OapErN9cww-FPXgOoatLclIoOP4NmT?usp=drive_link).
- [`sample_data.pk`](https://drive.google.com/file/d/1rzJSeXy4Csgx3xRYm-Gw5T1HJdU8r87j/view?usp=drive_link) contains the perturbed first paragraph of Wikipedia biographies that were used for the experiments in the paper.
- [`all_summaries.pk`](https://drive.google.com/file/d/16aYcI2UwtBkkD5HKI33p1Z4SR5dtyqiL/view?usp=drive_link) contains the generated summaries for the Wikipedia biographies using all the models that we experimented with.
- [`data_for_plot.pk`](https://drive.google.com/file/d/1nWRP2BbpV7zdVWuXiKzxoT-iXd84lEfL/view?usp=drive_link) contains the data needed to generate the plots in our paper.

## Load the data
- To load the data, please use the `load_data.ipynb` notebook. It walks through how to load the data as well as how to compute hallucination rates and create the heatmap in the paper.
- If you'd like to generate the plots, please follow the `plot.ipynb` notebook.
