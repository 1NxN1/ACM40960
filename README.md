# ACM40960
Assignment
# Automatic License Number Plate Detection And Recognition
## _Table of Content_

- [_Automatic License Number Plate Detection And Recognition_]()
  - [_Background_](#background)
  - [_Install_](#install)
  - [_Usage_](#usage)
  - [_Example_](#example)
  - [_Performance_](#performance)
  - [_License_](#license)
 
## _Background_

> License plate recognition system (Vehicle License Plate Recognition) is an application of computer video image recognition technology in vehicle license plate recognition. Usually a license plate recognition system mainly includes the following four parts: vehicle image acquisition, license plate positioning, license plate character segmentation, license plate recognition Character recognition. This project is implemented through OpenCV and convolutional neural network(CNN).

## _Install_

> This project uses opencv and Pytorch. Go check them out if you don't have them locally installed.
```sh
pip install opencv-python==4.6.0.66
conda install pytorch torchvision torchaudio cpuonly -c pytorch
pip install imutils==0.5.4
pip install matplotlib==3.3.4
```
## _Usage_
> Firstly, CNN Model must be trained if there is no 'model.pkt'
```sh
python3 train.py
```
> Then, we can detect an image by input an image name
```sh
python3 Detect_Plate.py --target "the name of image"
```

## _Example_

```sh
python3 Detect_Plate.py --target images/Cars1.png
```

## _Performance_
![image](https://github.com/Figure_1.png)
![image](https://github.com/Figure_2.png)
![image](https://github.com/Figure_3.png)
![image](https://github.com/Figure_4.png)
## _License_
[MIT](LICENSE)
