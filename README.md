# MSDS19006_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes


[Dataset](https://drive.google.com/drive/u/2/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR)


[Datset for class imbalance](https://drive.google.com/drive/u/2/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR)



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

