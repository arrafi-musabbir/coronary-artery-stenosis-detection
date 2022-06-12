# coronary-artery-stenosis-detection
Using Faster RCNN with 'inception resNetv2' as backbone architecture to detect stenosis regions within coronary artery from coronary CT angiography.

I followed this publication by Danilov et al. namely [Real-time coronary artery stenosis detection based on modern neural networks](https://www.nature.com/articles/s41598-021-87174-2)[^1] to detect stenosis region of coronary artery. Here the authors showed a brief comaparison between eight object dection architectures in coronary stenosis detection. Within them faster RCNN scored the highest. 

# Methodology
I utilized the object-detection-API by tensorflow to train our model and detect stenosis region of coronary artery. 

# Dataset
Dataset is accessible by the following link: [Angiographic dataset for stenosis detection](https://data.mendeley.com/datasets/ydrm75xywg/1)[^2]


# Reference 

[^1]: Danilov, V.V., Klyshnikov, K.Y., Gerget, O.M. et al. Real-time coronary artery stenosis detection based on modern neural networks. Sci Rep 11, 7582 (2021),  [https://doi.org/10.1038/s41598-021-87174-2](https://doi.org/10.1038/s41598-021-87174-2).
[^2]: Danilov, Viacheslav; Frangi, Alejandro; Klyshnikov, Kirill; Kutikhin, Anton; Ovcharenko, Evgeny; Gerget, Olga (2021), “Angiographic dataset for stenosis detection”, Mendeley Data, V1, [https://doi.org/10.17632/ydrm75xywg.1](https://doi.org/10.17632/ydrm75xywg.1)
