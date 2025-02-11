# VHRTreeSpecies
## Dataset Description
The VHRTreeSpecies dataset includes very high-resolution RGB satellite images obtained from Google Earth Pro, featuring 15 dominant tree species from diverse forest regions of Türkiye. The species labels were derived from the General Directorate of Forestry (OGM) Forest Stand Type Maps to ensure accurate classification. The dataset consists of 256x256 pixel patches extracted from large-scale forest imagery, preprocessed and structured to facilitate deep learning experiments.

The dataset comprises 15 dominant tree species, including Abies spec. (Fir), Alnus spec. (Alder), Carpinus (Hornbeam), Castanea spec. (Chestnut), Cedrus (Cedar), Fagus spec. (Beech), Juniperus spec. (Juniper), Picea spec. (Spruce), Pinus brutia (Red Pine), Pinus nigra (Black Pine), Pinus pinaster (Maritime Pine), Pinus pinea (Stone Pine), Pinus sylvestris (Scots Pine), Quercus petraea (Sessile Oak), and Quercus robur (English Oak).

![dataset_description](https://github.com/sulenurtopgull/VHRTreeSpecies/blob/main/Figure2_remotely_sensed_data.jpg)


## Benchmark Models
The dataset has been evaluated using state-of-the-art deep learning models, including:
- **CNN Models:** ResNet50, ResNet101, VGG16, ResNeXt50, InceptionV3, ConvNeXt-T, EfficientNet.

- **Transformer Models:** ViT, DeepViT, Swin Transformer, CaiT, SegFormer (b0, b1, b2).

- **YOLO Models:** YOLOv8-l, YOLOv11-l.
