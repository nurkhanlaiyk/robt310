## Depth Estimation using Deep Learning and Image processing


## Demo
* Open the new colab notebook: My Drive -> New -> More -> Google Collabotary
* To check the demo version, clone the github repository
* Run `!git clone https://github.com/nurkhanlaiyk/robt310.git`

## Pre-trained Models
* [NYU Depth V2](https://drive.google.com/file/d/19dfvGvDfCRYaqxVKypp1fRHwK7XtSjVu/view?usp=sharing) (165 MB)
* [KITTI](https://drive.google.com/file/d/19flUnbJ_6q2xtjuUQvjt1Y1cJRwOr-XY/view?usp=sharing) (165 MB)



## Training
* Run `python train.py --data nyu --gpus 4 --bs 8`.

## Evaluation
* Download, but don't extract, the ground truth test data from [here](https://s3-eu-west-1.amazonaws.com/densedepth/nyu_test.zip) (1.4 GB). Then simply run `python evaluate.py`.

