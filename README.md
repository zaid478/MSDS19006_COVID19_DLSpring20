# MSDS19006_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes


[Dataset](https://drive.google.com/drive/u/2/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR)


[Datset for class imbalance](https://drive.google.com/drive/u/2/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR)


# Models for different experiments
[VGG 16 (Finetuning fully connected layers)](https://drive.google.com/open?id=1169PhP-oXsVbuE77zl2uMLX0tfhEQfK0)
[VGG 16 (Finetuning the whole network)](https://drive.google.com/open?id=1-r3yqkUAkfcxSEga8EzfvPrfRD4mhEyb)
[ResNet 18 (Finetuning fully connected layers)](https://drive.google.com/open?id=12QLco6YjpR9AlJllRgMaf7xpAxy7HSt3)
[ResNet 18 (Finetuning the whole network)](https://drive.google.com/open?id=1WDZ2Cn8ifS9M17YKKVoU9ZxELCRWQn36)


# Experiments showing confusion matrices

## 1) Finetuning only fully connected layers:
#####   a) VGG 16: (Testing set results)
        |Infected | Normal |
        | 486     | 129    |
        | 37      | 848    |
       
#####   a) ResNet 18: (Testing set results)
        |Infected | Normal |
        | 569     | 46     |
        | 77      | 808    |

## 2) Finetuning the entire network:
#####   a) VGG 16: (Testing set results)
        |Infected | Normal |
        | 579     | 36     |
        | 26      | 859    |
       
#####   a) ResNet 18: (Testing set results)
        |Infected | Normal |
        | 591     | 24     |
        | 22      | 863    |




# Models for class imbalance dataset
[VGG 16 without focal loss](https://drive.google.com/open?id=19rnpES2_eCc1hn9P1yXs6qi9nW1fff4-)
[ResNet 18 without focal loss](https://drive.google.com/open?id=1rath-cgyO7LOeMBR83d6fQ4Mjl0_iowF)
[VGG 16 with focal loss](https://drive.google.com/open?id=1Nbiyc_XLxAANYBTo70qA06CpezOow8aG)
[ResNet 18 with focal loss](https://drive.google.com/open?id=1PYMm63H-p2mulAELC-ePqvn92ieK5kQw)
