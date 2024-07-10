# AGE: Amharic, Ge’ez, and English Parallel Dataset

## Overview

The AGE dataset is an open-source tripartite alignment of Amharic, Ge’ez, and English parallel sentences. This dataset aims to address the lack of high-quality resources for low-resource languages like Amharic and Ge’ez, facilitating the development of Natural Language Processing (NLP) models.



## Data Collection

Our dataset was sourced from diverse materials, and we removed excessively disordered portions to ensure quality. The dataset development process is illustrated in the accompanying figure.

Below is an example row:
```
[
    {
        "amh": "ንጉሡ ዳዊትም ሸመገለ ዕድሜውም በዛ፤ ልብስም ደረቡለት፥ ነገር ግን አይሞቀውም ነበር።",
        "gez": "ወዳዊትሰ ንጉሥ ልህቀ ወኀለፈ መዋዕሊሁ ወይከድንዎ አልባሰ ወኢያመውቆ ።",
        "eng": "Now king David was old and stricken in years; and they covered him with clothes, but he gat no heat."
    },
    {
        "amh": "ባሪያዎቹም። ለጌታችን ለንጉሡ ድንግል ትፈለጋለች፤ በንጉሡም ፊት ቆማ ታገልግለው፥ በጌታችንም በንጉሡ ብብት ተኝታ ታሙቀው አሉት።",
        "gez": "ወይቤሉ ደቁ ለዳዊት ይኅሥሡ ለእግዚእነ ለንጉሥ ወለተ ድንግለ ወያምጽእዋ ኀበ ንጉሥ ወትሰክብ ምስሌሁ ወተሐቅፎ ወታስተማውቆ ወይመውቅ እግዚእነ ንጉሥ ።",
        "eng": "Wherefore his servants said unto him, Let there be sought for my lord the king a young virgin: and let her stand before the king, and let her cherish him, and let her lie in thy bosom, that my lord the king may get heat."
    },

]
```

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

