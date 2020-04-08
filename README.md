VSE_CA1
---

## SECTION 1 : PROJECT TITLE
Project Title

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



---
## SECTION 6 : PROJECT REPORT / PAPER

amab.pdf
`<Github File Link>` : <https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB/blob/master/ProjectReport/amab.pdf>

---
## SECTION 7 : MISCELLANEOUS

ChatBot.xlsx
`<Github File Link>` : <https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB/blob/master/Miscellaneous/ChatBot.xlsx>

---
