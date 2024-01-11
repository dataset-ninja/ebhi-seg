**EBHI-Seg: Enteroscope Biopsy Histopathological Hematoxylin and Eosin Image Dataset for Image Segmentation Tasks** is a dataset for instance segmentation, semantic segmentation, and object detection tasks. It is used in the medical industry. 

The dataset consists of 2228 images with 12985 labeled objects belonging to 6 different classes including *andadenocarcinoma*, *low-grade intraepithelial neoplasia*, *polyp*, and other: *high-grade intraepithelial neoplasia*, *normal*, and *serrated adenoma*.

Images in the EBHI-Seg dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. There are 2 (0% of the total) unlabeled images (i.e. without annotations). There are no pre-defined <i>train/val/test</i> splits in the dataset. The dataset was released in 11 by the MIaMIA research group, China.

<img src="https://github.com/dataset-ninja/ebhi-seg/raw/main/visualizations/poster.png">
