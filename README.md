# Image Classification Program

> Image classifier for Philips products.

---
## Table of Contents

- [Installation of Docker Image](#installation)
- [Clone](#clone)
- [Setup](#setup)
- [Presentation](#presentation)
- [Colab](#colab)
- [Dataset Description](#dataset)
- [Training](#training)
- [Validation](#validation)
- [Contact](#contact)
---

## Installation

- After cloning the repository, please remove README.md file in model/val-images
- Before building Docker image, please add test images into model/val-images folder.
- After cloning, please apply Docker command below in the /model/ directory of the project to prevent path errors:

### Clone

```shell
$ git clone https://github.com/BxCvd1LZVDCvW74I/model.git
```
### Setup
- Tested on Docker Toolbox Version: Docker version 19.03.1, build 74b1e89e8a on Windows 10 Home edition
```shell
$ docker build -t philips-case -f Dockerfile .
```
### Presentation

- For this case, I prepared a presentation about my approach to establish an image classification model, including dataset description and training results.

- Link: <a href="https://drive.google.com/file/d/1Lv6_2hVZcOBVt-ipI28CPd2tsc0xkUfU/view?usp=sharing
" target="_blank">`Presentation`</a>

## Colab

- In this Google Colab notebook, I reproduced the results due to possible errors from Docker Toolbox for Windows 10 Home edition:
- Please run the notebook until cloning the repository.
- After cloning this repository is done, please upload test images to model/val-images folder and run the other cells to reproduce results.
- Link: <a href="https://colab.research.google.com/drive/1xVP4TRCD_y6Azh5uwbZkXCUxDveaWfyM" target="_blank">`Colab Notebook`</a>

## Training

<img src="https://i.ibb.co/Tm8ypY0/tr.jpg" width="300">

## Validation

<img src="https://i.ibb.co/Br7GW2X/cm.jpg" width="300">

## Dataset

Image dataset created by using product review videos from Youtube.
- Wake up light : 13.311 images
- Tootbrush : 13.999 images
- Shaver : 14.519 images
- Smart Baby Bottle : 10.503 images

## Contact

I'll be checking my e-mail through the competition. Contact information:
- E-mail: <a href="mailto:mburakbozbey@outlook.com" target="_blank">`mburakbozbey@outlook.com`</a>
- Website at <a href="https://mburakbozbey.github.io/" target="_blank">`mburakbozbey.github.io`</a>
- Linkedin at <a href="https://www.linkedin.com/in/mburakbozbey/" target="_blank">`@mburakbozbey`</a>
