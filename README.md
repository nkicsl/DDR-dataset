# OIA-DDR

A General-purpose High-quality Dataset for Diabetic Retinopathy Classification, Lesion Segmentation and Lesion Detection

You can download OIA-DDR from either Baidu Drive or Google Drive.

- OIA-DDR on Baidu Drive: [DDR dataset](https://pan.baidu.com/s/1560JK2pzxTN9Ny1TcmNasQ "悬停显示") PWD:ue0t
- OIA-DDR on Google Drive: [DDR dataset](https://drive.google.com/drive/folders/1z6tSFmxW_aNayUqVxx6h6bY4kwGzUTEC "悬停显示")

The dataset is a zip file split into 10 chunks, and must first be combined into a single zip archive before extraction. To fully unpack the dataset:

```shell
cat DDR-dataset.zip.0* > DDR-dataset.zip
unzip DDR-dataset.zip
```

If you make use of the DDR dataset, please cite our following paper:

    @article{LI2019,
      title = "Diagnostic Assessment of Deep Learning Algorithms for Diabetic Retinopathy Screening",
      author = "Tao Li and Yingqi Gao and Kai Wang and Song Guo and Hanruo Liu and Hong Kang",
      journal = "Information Sciences",
      volume = "501",
      pages = "511 - 522",
      year = "2019",
      issn = "0020-0255",
      doi = "https://doi.org/10.1016/j.ins.2019.06.011",
      url = "http://www.sciencedirect.com/science/article/pii/S0020025519305377",
    }

# License
The OIA-DDR dataset, including its images, annotations, labels, and other dataset-related materials, is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0).
Under this license, you are free to share and adapt the dataset for non-commercial purposes, provided that:

- Attribution (BY): Appropriate credit must be given to the original authors, and the corresponding DDR paper should be cited.
- NonCommercial (NC): The dataset may not be used for commercial purposes without prior written permission from the authors.
- ShareAlike (SA): Any adapted or derivative materials must be distributed under the same or a compatible license.

For details, please refer to the [CC BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
Any source code or scripts provided in this repository remain subject to the MIT License, unless otherwise stated.
For commercial use or other permissions beyond the scope of CC BY-NC-SA 4.0, please contact the authors.
