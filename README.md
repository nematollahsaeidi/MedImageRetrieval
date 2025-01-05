# Evaluating Pre-trained Convolutional Neural Networks and Foundation Models as Feature Extractors for Content-based Medical Image Retrieval

## Summary
Medical image retrieval aims to identify similar images for a given query image in a database, supporting tasks like diagnosis, treatment planning, and education. Content-based medical image retrieval (CBMIR) focuses on extracting features directly from the images, such as color, texture, and shape. Pre-trained convolutional neural networks (CNNs) have been widely used for CBMIR, but recent advancements in foundation models for computer vision present an opportunity to explore their potential for superior performance.

In this study, we evaluated several pre-trained feature extractors, including CNNs (VGG19, ResNet-50, DenseNet121, and EfficientNetV2M) and foundation models (MedCLIP, BioMedCLIP, OpenCLIP, CONCH, and UNI), on a subset of the MedMNIST V2 dataset. The dataset comprises eight types of 2D and 3D medical images. Additionally, we analyzed the effect of image size on retrieval performance.

Key findings:
- For 2D datasets, foundation models significantly outperform CNNs, with UNI delivering the best overall performance across all datasets and image sizes.
- For 3D datasets, CNNs and foundation models exhibit more comparable performance, with CONCH achieving the best results overall.
- Larger image sizes yield slightly better performance, especially for 2D datasets, but competitive results can still be achieved with smaller image sizes.

Our codes for generating and reproducing the results are available on GitHub.

## Preprint
The preprint of the paper is available on arXiv:  
[https://www.arxiv.org/abs/2409.09430](https://www.arxiv.org/abs/2409.09430)

## Code
The implementation can be found in the following GitHub repository:  
[https://github.com/masih4/MedImageRetrieval.git](https://github.com/masih4/MedImageRetrieval.git)

## Citation
If you find our work useful, please cite it as follows:
```bibtex
@article{mahbod2024evaluating,
  title={Evaluating Pre-trained Convolutional Neural Networks and Foundation Models as Feature Extractors for Content-based Medical Image Retrieval},
  author={Mahbod, Amirreza and Saeidi, Nematollah and Hatamikia, Sepideh and Woitek, Ramona},
  journal={arXiv preprint arXiv:2409.09430},
  year={2024}
}
