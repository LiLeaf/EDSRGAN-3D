# Super Resolution by Neural Networks
## Introduction
Implementation for the super resolution of both 2D and 3D images. Involved Neural Networks: EDSR, SR-Resnet Residual, SRGAN, WDSR, SRCNN.

## Authors
[YingDa Wang](https://github.com/yingDaWang-UNSW "GitHub Account")<br>
[Name](social media account link "hover information")<br>
[Name](social media account link "hover information")<br>
[Name](social media account link "hover information")<br>
...

(Department, UNSW)

## Installation
**Version 0.1**<br>
This software is compatible with windows, mac, and linux  machines. It will install anaconda3, along with the necessary python packages in a containerised anaconda environment. <br>

**Linux and Mac**

Open a terminal window at the directory where the file “installSR.sh” is located and type “bash installSR.sh”. 



Step1: 

Open a “Anaconda cmd Prompt” terminal window at the directory where the file “installSR.sh” is located and  type “bash installSR.sh”. 
```
$ bash installSR.sh
```

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step1.png)


Step2: 

Please input this command: 

For Mac, please use

```
$ bash installSRMac.sh
```

For Linux, please use

```
$ bash installSRLinux.sh
```

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step2.png)

Step3: 

Always type “y” for yes if it is required. 

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step3.png)

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step4.png)

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step5.png)

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step6.png)

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step7.png)

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step8.png)

Step4: 

Please input this command to run the software: 

For Mac, please use
```
$ bash runSRMac.sh
```

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step9.png)

For Linux, please use
```
$ bash runSRLinux.sh
```

<br>FOR ADVANCED USERS: if you already have anaconda3, or wish to install the packages yourself, a full list of conda packages used by this software are shown below:<br>

```
conda install tensorflow=1.13.0 

conda install matplotlib 

conda install pillow 

conda install -c conda-forge gooey  

pip install tensorlayer==1.11 

pip install argparse 
```

<br> If you do not have the anaconda3, you may download it via this link:<br>
For Linux system, click this link:
https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh

For Windows system, this link instead:
https://repo.anaconda.com/archive/Anaconda3-2019.03-Windows-x86_64.exe

Then, open a “Anaconda Prompt” terminal window shown in the below image.  

![image](https://github.com/LiLeaf/SRInstall_images/blob/master/step11.png)

The specific installation steps are as follow. Always type "y" for "yes".
```
conda update -n base -c defaults conda

conda create --name srRockEnv2 python=3.6

conda activate srRockEnv2
```

For linux system, you may prefer to type "conda install tensorflow-gpu=1.13.0":
```
conda install tensorflow-gpu=1.13.0
```

For Mac system, "conda install tensorflow=1.13.0" instead:
```
conda install tensorflow=1.13.0
```

Then, please type these lines:
```
conda install matplotlib

conda install pillow

conda install -c conda-forge gooey

pip install tensorlayer==1.11

pip install argparse
```
