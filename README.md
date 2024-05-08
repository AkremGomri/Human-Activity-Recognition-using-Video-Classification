
# Human Activity Recognition using Video Classification

This project takes its insperation from this [research paper](https://learnopencv.com/introduction-to-video-classification-and-human-activity-recognition/) within the context of a university project at UPEC in Paris. 

Due date: 03/03/2024

# Getting Started
## Run With Google Colab

- First download the [dataset](https://www.crcv.ucf.edu/data/UCF50.rar) and upload it to your drive under `/content/drive/MyDrive/Human-Activity-Recognition-using-Video-Classification/`.

For the rest, the best solution to proceed with is by following the steps mentionned in this [website](https://saturncloud.io/blog/how-can-i-run-notebooks-of-a-github-project-in-google-colab/) .

Otherwise, you can still follow the following approach.

- Download this [file](https://github.com/AkremGomri/Human-Activity-Recognition-using-Video-Classification/archive/refs/heads/main.zip) and extract it locally.

- Now open any of the files in `Colab Notebooks`


## Run Locally With Jupyter

In order to run the project locally, you need to follow these steps:

- First, download the [dataset](https://www.crcv.ucf.edu/data/UCF50.rar), extract it inside a folder.

- Then open shell or cmd in this folder and run the following command :

```bash
  git clone https://github.com/AkremGomri/Human-Activity-Recognition-using-Video-Classification.git
```

Cloning this project might take a few minutes due to the large files that it contains. So I recommand you to be patient.

But don't worry about their size on your disk, the size of all the files combined do not exceed 300 MB.

- Now you need to compress the folder to zip file, then open jupyter notebook and upload the zip file.

- Now you need to extract the file,so create a new python file in jupyter to run the following command to extract the file :

``` bash
import zipfile as zf
files = zf.ZipFile("Human-Activity-Recognition-using-Video-Classification.zip", 'r')
files.extractall('Extracted_file')
files.close()
```
Feel free to change the name of the ZipFile as well as the Extracted_file name.

- Lastly, open any .ipynb file and comment out the first code cell as that cell is used to connect with Google Colab.

## Learned Skills
Deep Learning, Computer Vision, CNN, LSTM, SlowFusion, Pose Detection, TensorFlow

## Authors

- [@AkremGomri](https://github.com/AkremGomri/)

## Contact
[![gmail](https://img.shields.io/badge/gmail-E1574A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gomriakrem1@gmail.com)
[![github](https://img.shields.io/badge/github-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AkremGomri/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akrem-gomri/)
