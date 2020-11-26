## Toxicity-analysis
This is a repo to document experiments on classifying toxicity data using various NLP techniques.The Jupyter notebook attached has description of different models being tried.

### Dataset:
The data is used from an open sources Wikimedia foundation project from Wikipedia talk pages. Around 160k comments annotated by 10 persons from Crowdflower platform. All comments are labelled on more than one metric like hate, personal attack, toxicity etc. I have only used toxic label for these experiments.

Running the data preprocessing on the data can take sometime(espcially lemmatisation), you can get the both versions of the data. Raw and Processed [here](https://drive.google.com/drive/folders/1rDPQitRgAyOZZPUcEhdE4Ky7Zr15cQof?usp=sharing).

I have also recently run an experiment with Distil BERT, these are contextual embeddings and catch much better relations amongst word than traditional methods.
Link to google colab: https://colab.research.google.com/drive/19xRn3wMHfc10pMKsLE5_JYxkOoqAFQKf#scrollTo=gi_rXkUjAXlI 
