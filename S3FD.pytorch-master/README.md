
## Dataset: F irst download the wider face dataset (training, validation, testing and
face annotation) from this link http://shuoyang1213.me/WIDERFACE/.
### Requirement: Pytorch, OpenCV, NumPy and easydict library.
## Setup and Modification:
● First, make the “WIDER” folder inside the “S3FD” folder. Then download the wider face dataset and move the “wider face dataset” file inside the “WIDER” folder.
● Modify the data/config.py file. Set the absolute path of the S3FD folder in “_C.HOME variable”.
● Run the “python prepare_wider_data.py” c ommand for preparing the data.
● Run the “python train.py --batch_size 4 --dataset face” command for training the model.
● Run the “python demo.py” command for testing the model.
