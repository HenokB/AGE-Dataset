# AGE: Amharic, Ge’ez, and English Parallel Dataset

## Overview

The AGE dataset is an open-source tripartite alignment of Amharic, Ge’ez, and English parallel sentences. This dataset aims to address the lack of high-quality resources for low-resource languages like Amharic and Ge’ez, facilitating the development of Natural Language Processing (NLP) models.

## Abstract

African languages are underrepresented in NLP due to a scarcity of training data. Low-resource languages, such as Amharic and Ge’ez, cannot leverage modern NLP methods due to this lack of high-quality datasets. The AGE dataset introduces a novel collection of 1,000 Ge’ez-centered sentences from sources like news and novels. We also developed a model from a multilingual pre-trained language model, achieving BLEU scores of 12.29 and 30.66 for English to Ge’ez and Ge’ez to English translations, respectively, and 9.39 and 12.29 for Amharic-Ge’ez and Ge’ez-Amharic translations.

## About Ge'ez (ግዕዝ)

Ge’ez, also known as Ethiopic, is one of the oldest Semitic languages, with an alphabet still in use today. Although it is not actively spoken, Ge’ez remains the liturgical language for several religious communities in Ethiopia and Eritrea. The literature of Ge’ez includes many medieval and early modern texts, mainly associated with the Ethiopian Orthodox Tewahedo Church.

## Related Works

Developing Machine Translation (MT) models for Ge’ez faces significant challenges due to the lack of public data. Previous attempts to compile parallel corpora for Ge’ez to English and Ge’ez to Amharic MT tasks have been unsatisfactory.

## Results

Our dataset demonstrates a clear gradient in BLEU score performance across various language pairs. For Amharic-Ge’ez translations, the model achieved BLEU scores of 9.03 and 12.26 during evaluation, with slight improvements in the prediction phase. The Ge’ez-English language pair showed the highest scores, achieving 30.35 in evaluation and 30.66 in prediction.

## Data Collection

Our dataset was sourced from diverse materials, and we removed excessively disordered portions to ensure quality. The dataset development process is illustrated in the accompanying figure.

## Dataset Structure

The dataset is available in both CSV and JSON formats, with columns tagged for each language:

- `amh`: Amharic
- `gez`: Ge’ez
- `eng`: English


## Citation

If you use this dataset, please cite our paper:

```
@inproceedings{
  ademtew2024age,
  author    = {Henok Biadglign Ademtew and Mikiyas Girma Birbo},
  title     = {{AGE}: Amharic, Ge{\textquoteright}ez and English Parallel Dataset},
  booktitle = {5th Workshop on African Natural Language Processing},
  year      = {2024},
  url       = {https://openreview.net/forum?id=tHNfskz2WG}
}
```

## License

This dataset is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License. You are free to use and modify the source code, provided that you link back to this page in the footer. Please remove any analytics code included in the header of the website if you do not want it on your site.

