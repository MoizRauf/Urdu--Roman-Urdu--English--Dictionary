# Urdu-- Roman-Urdu -- English -- Dictionary

### About the dataset
The dataset contains 5916 trilingual Urdu -- Roman Urdu -- English terms. The parallel lexicon has been generated using  statistical machine translation approaches, word embeddings and parallel corpora for dictionary creation. The repository contains following files.

| File | Description |
|:--------:|:----:|
| Gold_Annotations.tsv  |  File contains 1000 trilingual pairs evaluated by human annotators.  |
| en_ur_rom.high.tsv |  File contains trilingual translations, having Urdu--Roman Urdu score between (.68,1)  |
| en_ur_rom.mid.tsv |  File contains trilingual translations, having Urdu--Roman Urdu score between (.33,.67)   |
| en_ur_rom.low.tsv |  File contains trilingual translations, having Urdu--Roman Urdu score between (.1,.32)  |


For more details regarding the data set, kindly refer the paper: (http://www.winlp.org/wp-content/uploads/2019/final_papers/139_Paper.pdf)
```
Moiz Rauf and Sebastian Padó. 2019. Learning Trilingual Dictionaries for Urdu -- Roman Urdu -- English.
Institut für Maschinelle Sprachverarbeitung, University of Stuttgart, Germany.
```
Or, if you are using ![](https://latex.codecogs.com/gif.latex?%5Ctext%7B%5CLaTeX%7D) then BibTeX entry is following.
```
@inproceedings{rauf19:_learn_trilin_diction_urdu,
  added-at = {2019-06-03T09:28:39.000+0200},
  address = {Florence, Italy},
  author = {Rauf, Moiz and Padó, Sebastian},
  biburl = {https://puma.ub.uni-stuttgart.de/bibtex/285a4246fa1a2402652d55f6427946840/sp},
  booktitle = {Proceedings of the ACL Workshop on Widening NLP},
  interhash = {d62b4cbe2e6943dfbc0bd9ffe4123472},
  intrahash = {85a4246fa1a2402652d55f6427946840},
  timestamp = {2019-06-04T09:28:42.000+0200},
  title = {Learning Trilingual Dictionaries for Urdu -- Roman Urdu -- English},
  year = 2019
}
```
