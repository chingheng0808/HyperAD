# HyperAVIRIS

## An Remote Sensing Datasets from [AVIRIS Data Portal](https://aviris.jpl.nasa.gov/)

The data is sourced from the AVIRIS Data Portal. We collected the HSI data between 2008 and 2012, and the original HSI data was partitioned into 256 × 256 sub-images, resulting in 1,735 HSI sub-images. We then applied k-means clustering to categorize the HSI sub-images into five types: City, Mountain, Forest, Farm, and Other. Any misclassified sub-images were manually corrected. From each class, we selected 200 HSI sub-images, forming a dataset of 1,200 sub-images in total. The dataset was then split into training, validation, and testing sets, consisting of 1,000, 100, and 100 HSI sub-images, respectively. 

## Download by `Google Drive`

### The training, validation, and testing datasets:

| Dataset                  | Link                                                                                                    | Size                 |
| ------------------------ | ------------------------------------------------------------------------------------------------------- | -------------------- |
| **_Training Dataset_**   | [[download link](https://drive.google.com/drive/folders/15PDZ-EQgnA_PDLWPEAo4DEl7yAXY7J5k?usp=sharing)] | 18.8GB, 1000 examples|
| **_Validation Dataset_** | [[download link](https://drive.google.com/drive/folders/11OMZ-CIjlMCufydZlLG3bmsHACkZnTKF?usp=sharing)] | 100 examples         |
| **_Testing Dataset_**    | [[download link](https://drive.google.com/drive/folders/1B2Pg43KIQnlt2T04lK0Zb6TmcHUQzbNI?usp=sharing)] | 100 examples         |

`Note: the data in all datasets are stored in .npy formats.`

# Reference

```bibtex
@misc{lee2024prompthsiuniversalhyperspectralimage,
      title={PromptHSI: Universal Hyperspectral Image Restoration Framework for Composite Degradation},
      author={Chia-Ming Lee and Ching-Heng Cheng and Yu-Fan Lin and Yi-Ching Cheng and Wo-Ting Liao and Chih-Chung Hsu and Fu-En Yang and Yu-Chiang Frank Wang},
      year={2024},
      eprint={2411.15922},
      archivePrefix={arXiv},
      primaryClass={eess.IV},
      url={https://arxiv.org/abs/2411.15922},
}
```

and

```bibtex
@ARTICLE{10474407,
  author={Hsu, Chih-Chung and Jian, Chih-Yu and Tu, Eng-Shen and Lee, Chia-Ming and Chen, Guan-Lin},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  title={Real-Time Compressed Sensing for Joint Hyperspectral Image Transmission and Restoration for CubeSat},
  year={2024},
  volume={62},
  number={},
  pages={1-16},
  keywords={Hyperspectral imaging;Real-time systems;Sensors;Decoding;Compressed sensing;Training;Task analysis;Compressed sensing;deep learning (DL);hyperspectral image (HSI);hyperspectral restoration;real-time applications},
  doi={10.1109/TGRS.2024.3378828}}
```
