VSE_CA1
---

## SECTION 1 : PROJECT TITLE
Mask R-CNN Segmantic Segmentation

---
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
In this assignment, we attempted to efficiently detect objects in an image while simultaneously generating a high-quality segmentation mask for each instance. 
The method adopted is the Mask R-CNN. It is a deep neural network aimed to solve semantic segmentation problem in machine learning or computer vision. There are two stages of Mask RCNN. 
First, it generates proposals about the regions where there might be an object based on the input image. Second, it predicts the class of the object, refines the bounding box and generates a mask in pixel level of the object based on the first stage proposal.  

---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | 
| :------------ |:---------------:| 
| IAN TAN ENG KIONG | A0120534W | 
| KHOO WEE BENG | A0195308Y | 



---
## SECTION 4 : USE CASE DEMO

![Splash image labelled](https://github.com/dion797/VSE_CA1/blob/master/Miscellaneous/sample.png)

---
## SECTION 5 : SETUP INSTRUCTIONS
### [ 1 ] Visual Studio (Install only if C++ build librarys has not been installed)

> downloaded Build Tools for Visual Studio 2019/Community/(Visual C++) from: https://https://visualstudio.microsoft.com/downloads/

### [ 2 ] CUDA 9.0

> install CUDA 9.0 from https://developer.nvidia.com/cuda-90-download-archive

### [ 3 ] cuDNN 

> install cuDNN for CUDA 9.0 

> https://developer.nvidia.com/rdp/cudnn-download

> Select Download cuDNN v7.6.5 (November 5th, 2019), for CUDA 9.0

### [ 4 ] Setup cocoapi 

> https://github.com/cocodataset/cocoapi

> Download zip file to local storage

> First go to cocoapi\PythonAPI\setup.py and change line 14 from:

> "extra_compile_args=['-Wno-cpp', '-Wno-unused-function', '-std=c99'],"

> to

> "extra_compile_args={'gcc': ['/Qstd=c99']},"

### [ 5 ] Setup Environment 

> Run Anaconda Prompt and execute the following commands

> conda create --name mask python=3.6

> activate mask

> conda install numpy cython

### [ 6 ] install cocoapi/PythonAPI 

> Still in Anaconda Prompt

> cd <PATH_OF_cocoapi/PythonAPI>

> python setup.py install

### [ 7 ] Setup Mask RCNN

> https://github.com/matterport/Mask_RCNN

> Download zip file to local storage

> cd <PATH_OF_Mask_RCNN>

> python setup.py install

> download file(https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5) to <PATH_OF_Mask_RCNN>

### [ 8 ] Setup Environment part 2

> Go back to Anaconda Prompt and activate mask

> pip install scikit-image keras==2.2.5 tensorflow==1.12.0 tensorflow-gpu==1.12.0 imgaug jupyter

> Exit Anaconda Prompt 

> copy datasets/fmask to <PATH_OF_Mask_RCNN>/datasets/fmask

> copy samples/fmask to <PATH_OF_Mask_RCNN>/datasets/fmask

### [ 9 ] Run

> Run Jupyter Notebook in path samples/fmask

## SECTION 6 : PROJECT REPORT / PAPER

amab.pdf
`<Github File Link>` : <https://github.com/dion797/VSE_CA1/blob/master/ProjectReport/Segmentation_Maskv2.docx>

---
## SECTION 7 : MISCELLANEOUS

---
