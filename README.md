# VHRTreeSpecies
## Dataset Description
The VHRTreeSpecies dataset includes very high-resolution RGB satellite images, featuring 15 dominant tree species from diverse forest regions of Türkiye. The species labels were derived from the General Directorate of Forestry (OGM) Forest Stand Type Maps to ensure accurate classification. The dataset consists of 256x256 pixel patches extracted from large-scale forest imagery, preprocessed and structured to facilitate deep learning experiments.

The dataset comprises 15 dominant tree species, including Abies spec. (Fir), Alnus spec. (Alder), Carpinus (Hornbeam), Castanea spec. (Chestnut), Cedrus (Cedar), Fagus spec. (Beech), Juniperus spec. (Juniper), Picea spec. (Spruce), Pinus brutia (Red Pine), Pinus nigra (Black Pine), Pinus pinaster (Maritime Pine), Pinus pinea (Stone Pine), Pinus sylvestris (Scots Pine), Quercus petraea (Sessile Oak), and Quercus robur (English Oak).

![dataset_description](https://github.com/sulenurtopgull/VHRTreeSpecies/blob/main/Figure2_remotely_sensed_data.jpg)


## Benchmark Models
The dataset has been evaluated using state-of-the-art deep learning models, including:
- **CNN Models:** ResNet50, ResNet101, VGG16, ResNeXt50, InceptionV3, ConvNeXt-T, EfficientNet.

- **Transformer Models:** ViT, DeepViT, Swin Transformer, CaiT, SegFormer (b0, b1, b2).

- **YOLO Models:** YOLOv8-l, YOLOv11-l.

## Models, Metric Results and Weights

|     Model     | Precision |  Recall  | F1 Score | Overall Accuracy (%)|
|:-------------:|:---------:|:--------:|:--------:|:-------------------:|
|   Resnet50    |   91.46   |   91.44  |  91.42   |        92.69        | 
|   Resnet101   |   91.19   |   90.77  |  90.93   |        92.29        | 
|    VGG16      |   90.03   |   90.55  |  90.22   |        91.21        | 
|   ResNeXt     |   93.61   |   94.28  |  93.87   |        94.69        | 
|   InceptionV3 |   92.05   |   91.38  |  91.57   |        92.77        | 
|   ConvNeXt    |   87.67   |   86.89  |  87.13   |        88.23        | 
|  EfficientNet |   86.20   |   86.62  |  86.04   |        87.84        | 
|   DeepViT     |   61.87   |   61.57  |  61.49   |        64.05        | 
|     Swin      |   84.09   |   83.73  |  83.52   |        85.39        | 
|     CaiT      |   45.83   |   45.06  |  45.13   |        47.63        | 
|  SegFormer-B0 |   94.86   |   92.96  |  93.74   |        94.71        |
|  SegFormer-B1 |   94.84   |   93.89  |  94.29   |        95.40        | 
|  SegFormer-B2 |   95.73   |   95.60  |  95.65   |        96.25        | 
|   YOLOv8-l    |   94.57   |   94.36  |  94.45   |        95.31        | 
|   YOLOv11-l   |   93.50   |   93.05  |  93.24   |        94.19        |

*The pre-trained models and weights can be found [here](https://drive.google.com/drive/folders/1j9ub972-85Gi3xIQyj9h3ZB7k_pusqUp?usp=drive_link)*

# Citation:
Please kindly cite our [paper](https://www.tandfonline.com/doi/full/10.1080/17538947.2025.2522394?src=) if this code and the dataset used in the study are useful for your research.

Sertel, Elif, and Sule Nur Topgul. 2025. “Comparative Analysis of Deep Learning Approaches for Forest Stand Type Classification: Insights from the New VHRTreeSpecies Benchmark Dataset.” International Journal of Digital Earth 18 (1). doi:10.1080/17538947.2025.2522394.
