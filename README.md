
# Small Object Detection on Drone Dataset

This project aims to enhance small object detection on the VisDrone dataset, which encompasses a comprehensive collection of aerial images. By studying the application of advanced deep learning models such as YOLOv8, YOLOv5, and EfficientDet, and employing preprocessing techniques like image slicing, we aim to improve detection rates for small objects in large scenes captured by drones.

## Project Overview

The primary goal of this project is to tackle the challenge of detecting small objects in aerial imagery, which has significant implications for applications like surveillance, environmental monitoring, and more. We explore the integration of the SAHI slicing method with YOLOv5, demonstrating remarkable performance improvements. Additionally, we analyze HICYOLOv5, an enhanced YOLOv5 model that introduces a dedicated prediction head for small objects, incorporates involution blocks, and integrates the CBAM attention mechanism.

## Dataset

The project utilizes the VisDrone-DET2019 dataset, which builds upon the VisDrone-DET2018 dataset. It comprises 8,599 images captured by drones at varying heights and locations, with over 540,000 bounding boxes annotated for ten predefined object categories, including pedestrians, vehicles, and bicycles.

## Methodology

1. **Model Selection and Preprocessing**: We focused on YOLOv8, YOLOv5, and HICYOLOv5 models due to their proven capabilities in object detection tasks. Preprocessing techniques like image slicing were employed to enhance small object detection.

2. **HICYOLOv5's Approach**: HICYOLOv5 introduces an additional prediction head specifically designed for small object detection, leveraging higher-resolution feature maps. It also incorporates involution blocks and the CBAM attention mechanism to improve performance and reduce computational costs.

## Results

- HICYOLOv5 demonstrated improvements of 6.42% in mAP@0.95 and 9.38% in mAP@0.5 compared to baseline models on the VisDrone-DET2019 dataset.
- The small object detection head, involution blocks, and CBAM attention module contributed to the enhanced performance in detecting small objects.


## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contributors

- [Jash Parikh](https://github.com/Jash7447)
- [Saahil Doshi](https://github.com/paridhijain19)
- [Paridhi Jain](https://github.com/paridhijain)
- [Kathan Dave](https://github.com/KathanrDave)

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to express our gratitude to the instructors and teaching assistants of the CSE 541 Computer Vision course for their guidance and support throughout this project.
