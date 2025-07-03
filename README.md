# Dementia Detection using Text Embeddings

This repository provides the notebook and associated code for reproducing the experiments presented in the research article **"Exploring LLM Embedding Potential for Dementia Detection Using Audio Transcripts."**. 

The experiments evaluate various text embedding methods (BERT, TF-IDF, GloVe, Gemma-2B, and Linq-Embed-Mistral) on transcripts from the PittCorpus (DementiaBank) dataset to detect indicators of Alzheimer's dementia. 

## Reproducibility

- **Notebook**: See the [notebooks/Dementia_Embeddings_Comparison.ipynb](notebooks/Dementia_Embeddings_Comparison.ipynb) file.
- **Dependencies**: Install required libraries with:

pip install -r requirements.txt

- **Note**: The embeddings generated with Linq-Embed-Mistral require high-performance computing resources and were precomputed externally.

## Data Availability

The data analyzed in this study were obtained from DementiaBank (PittCorpus) and are not publicly available. Access to these data can be requested through the DementiaBank official website: https://dementia.talkbank.org/access/English/Pitt.html, subject to approval by the data administrators.

## License

This project is licensed under the MIT License.
