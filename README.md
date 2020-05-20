# Urdu-- Roman-Urdu -- English -- Dictionary

### About the dataset
The dataset contains 5916 trilingual Urdu -- Roman Urdu -- English terms. The parallel lexicon has been generated using  statistical machine translation approaches, word embeddings and parallel corpora for dictionary creation. The repository contains following files.

| File | Description |
|:--------:|:----:|
| Gold_Annotations.tsv  |  File contains 1000 trilingual pairs evaluated by human annotators.  |
| en_ur_rom.high.tsv |  File contains trilingual translations, having Urdu--Roman Urdu score between (.68,1)  |
| en_ur_rom.mid.tsv |  File contains trilingual translations, having Urdu--Roman Urdu score between (.33,.67)   |
| en_ur_rom.low.tsv |  File contains trilingual translations, having Urdu--Roman Urdu score between (.1,.32)  |


For more details regarding the data set, kindly refer the paper: (https://www.aclweb.org/anthology/W19-3614/)
```
Moiz Rauf and Sebastian Padó. 2019. Learning Trilingual Dictionaries for Urdu -- Roman Urdu -- English.
Institut für Maschinelle Sprachverarbeitung, University of Stuttgart, Germany.
```
Or, if you are using ![](https://latex.codecogs.com/gif.latex?%5Ctext%7B%5CLaTeX%7D) then BibTeX entry is following.
```
@inproceedings{rauf-pado-2019-learning,
    title = "Learning Trilingual Dictionaries for {U}rdu {--} {R}oman {U}rdu {--} {E}nglish",
    author = "Rauf, Moiz  and
      Pad{\'o}, Sebastian",
    booktitle = "Proceedings of the 2019 Workshop on Widening NLP",
    month = aug,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    pages = "38--42",
    abstract = "In this paper, we present an effort to generate a joint Urdu, Roman Urdu and English trilingual lexicon using automated methods. We make a case for using statistical machine translation approaches and parallel corpora for dictionary creation. To this purpose, we use word alignment tools on the corpus and evaluate translations using human evaluators. Despite different writing script and considerable noise in the corpus our results show promise with over 85{\%} accuracy of Roman Urdu{--}Urdu and 45{\%} English{--}Urdu pairs.",
}
```
