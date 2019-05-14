# Human Somatic Label-free Bright-field Cell Images
### Abstract
This cell images dataset is collected using an ultrafast imaging system known as asymmetric-detection time-stretch optical microscopy ([ATOM](https://www.nature.com/articles/srep03656)) for training and evaluation. This novel imaging approach can achieve label-free and high-contrast flow imaging with good cellular resolution images at a very high speed. Each acquired image belongs to one of the four classes: THP1, MCF7, MB231 and PBMC. Our objective is to complement it with a high-speed classification system that is sensitive to the representations of different cell types, and meanwhile should ignore the noise caused by varying experimental settings. We have at our disposal two collections of images captured separately at different instances. Dataset 1 (small) contains over 8,000 samples of three types of cells (MCF7, PBMC, and THP1), while the other one Dataset 2 (large) is significantly larger, with over 900,000 cell images of MB231, MCF7, and THP1 cells.

### Information

* Dataset 1 (small)

|           |    Train    |  Validation |     Test    |              |
|:---------:|:-----------:|:-----------:|:-----------:|:------------:|
|    THP1   |    28450    |    11381    |    17138    |     56969    |
|    PBMC   |    10677    |     4230    |     6316    |     21223    |
|    MCF7   |     4210    |     1724    |     2549    |     8483     |
| **Total** | 43337 (50%) | 17335 (20%) | 26003 (30%) | 86675 (100%) |

**Notice:** The small dataset has been divided into Train/Validation/Test sets already for user convinence, and we also provide the separate "train.txt", "val.txt", and "test.txt" files to indicate the image paths and labels. The "label.txt" file gives the mapping between the sematic cell names and their corresponding digital labels.

**Download:** small.part1.rar -> small.part2.rar

* Dataset 2 (large)

|           | No. of Samples |
|:---------:|:--------------:|
|    THP1   |     200951     |
|    MCF7   |     374427     |
|   MB231   |     343394     |
| **Total** |     918772     |

**Download:** large.part01.rar -> large.part16.rar

* Dataset 3 (augmented)

|           |    Train     |  Validation |     Test    |               |
|:---------:|:------------:|:-----------:|:-----------:|:-------------:|
|    THP1   |    166474    |    38450    |    51076    |     256000    |
|    PBMC   |    208819    |    48054    |    64127    |     321000    |
|    MCF7   |    245767    |    56623    |    75610    |     378000   |
|    MB231  |    227190    |    52623    |    70187    |     350000   |
| **Total** | 848250 (65%) | 195750 (20%)| 261000 (30%)| 86675 (100%) |

**Download:** Augmented.part01.rar -> Augmented.part22.rar

**Notice:** The augmented dataset has been divided into Train/Validation/Test sets already.

### Citation

* IEEE

[1] Nan Meng, Edmund Lam, Tsia, Kevin Kin Man, So, Hayden Kwok-Hay, "Human somatic label-free bright-field cell images", IEEE Dataport, 2018. [Online]. Available: http://dx.doi.org/10.21227/H2QW97. Accessed: Mar. 13, 2019.

* Bibtex

Data
```
@data{h2qw97-18,
  doi = {10.21227/H2QW97},
  url = {http://dx.doi.org/10.21227/H2QW97},
  author = {Meng, Nan and Lam, Edmund and Tsia, Kevin Kin Man and So, Hayden Kwok-Hay},
  publisher = {IEEE Dataport},
  title = {Human somatic label-free bright-field cell images},
  year = {2018}
}
```

Paper
```
@article{Meng2018Largescale,
  title = {Large-scale Multi-class Image-based Cell Classification with Deep Learning},
  author = {Meng, Nan and Lam, Edmund and Tsia, Kevin Kin Man and So, Hayden Kwok-Hay},
  journal = {IEEE journal of biomedical and health informatics},
  year = {2018},
  publisher = {IEEE}
}
```
