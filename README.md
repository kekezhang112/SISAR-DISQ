# Learning-Based Quality Assessment for Image Super-Resolution
This repository contains the brief description of the SISAR dataset and DISQ code. If you use our dataset or code, or our work is useful for your research, please consider citing: 
```
@ARTICLE{9512504,
  author={Zhao, Tiesong and Lin, Yuting and Xu, Yiwen and Chen, Weiling and Wang, Zhou},
  journal={IEEE Transactions on Multimedia}, 
  title={Learning-Based Quality Assessment for Image Super-Resolution}, 
  year={2022},
  volume={24},
  number={},
  pages={3570-3581},
  doi={10.1109/TMM.2021.3102401}}
  ```
  ## Abstract
Image Super-Resolution (SR) techniques improve visual quality by enhancing the spatial resolution of images. Quality evaluation metrics play a critical role in comparing
and optimizing SR algorithms, but current metrics achieve only limited success, largely due to the lack of large-scale quality databases, which are essential for learning accurate and robust SR quality metrics. In this work, we first build a large-scale SR image database using a novel semi-automatic labeling approach, which allows us to label a large number of images with manageable human workload. The resulting SR Image quality database with Semi-Automatic Ratings (SISAR), so far the largest of SR-IQA database, contains 12,600 images of 100 natural scenes. We train an end-to-end Deep Image SR Quality (DISQ) model by employing two-stream Deep Neural Networks (DNNs) for feature extraction, followed by a feature fusion network for quality prediction. Experimental results demonstrate that the proposed method outperforms state-of-the-art metrics and achieves promising generalization performance in cross-database tests. The SISAR database and DISQ model will be made publicly available to facilitate reproducible research.
## Download
You can download the SISAR dataset and DISQ code from this [link](https://115.com/s/sw6id5f3hho?password=da98&#).

## Requirements
Python 3.7<br />
Tensorflow-gpu 1.15.0<br />
Tflearn 0.5.0<br />
The detailed instructions can be found in the code.
