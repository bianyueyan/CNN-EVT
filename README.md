# Identifying Patients with Acute Ischemic Stroke within a Six-Hour Window for the Treatment of Endovascular Thrombectomy Using Deep Learning and Perfusion Imaging
Hongyu Gao, [Yueyan Bian](https://github.com/bianyueyan), Gen Cheng, Huan Yu, Yuze Cao, Huixue Zhang, Jianjian Wang, Qian Li, Qi Yang and Lihua Wang

## Abstract
>  It is critical to identify the stroke onset time of patients with acute ischemic stroke (AIS) for the treatment of endovascular thrombectomy (EVT). However, it is challenging to accurately ascertain this time for patients with wake-up stroke (WUS). The current study aimed to construct a deep learning approach based on computed tomography perfusion (CTP) or perfusion weighted imaging (PWI) to identify a 6-hour window for patients with AIS for the treatment of EVT. We collected data from 377 patients with AIS, who were examined by CTP or PWI before making a treatment decision. Cerebral blood flow (CBF), time to maximum peak (Tmax), and a region of interest (ROI) mask were preprocessed from the CTP and PWI. We constructed the classifier based on a convolutional neural network (CNN), which was trained by CBF, Tmax, and ROI masks to identify patients with AIS within a 6-hour window for the treatment of EVT. We compared the classification performance among a CNN, support vector machine (SVM), and random forest (RF) when trained by five different types of ROI masks. To assess the adaptability of the classifier of CNN for CTP and PWI, which were processed respectively from CTP and PWI groups. Our results showed that the CNN classifier had a higher performance with an area under the curve (AUC) of 0.935, which was significantly higher than that of support vector machine (SVM) and random forest (RF) (p = 0.001 and p = 0.001, respectively). For the CNN classifier trained by different ROI masks, the best performance was trained by CBF, Tmax, and ROI masks of Tmax >6 s. No significant difference was detected in the classification performance of the CNN between CTP and PWI (0.902 vs. 0.928; p = 0.557). The CNN classifier trained by CBF, Tmax, and ROI masks of Tmax >6 s had good performance in identifying patients with AIS within a 6-hour window for the treatment of EVT. The current study indicates that the CNN model has potential to be used to accurately estimate the stroke onset time of patients with WUS.

## Network Architecture
![Figure1](https://user-images.githubusercontent.com/20896490/215727021-73a03782-4007-4d32-8a92-274db7f87b7b.jpg)

## Visual Comparison Results
![Figure5](https://user-images.githubusercontent.com/20896490/215727256-6178959f-1ef9-4b91-82cc-98fb122776d5.jpg)

## Data
We are preparing a open source dataset **CNN-EVT**, which contains 377 cases of data. 

**Acknowledgment**: These data were collected and proecssed by thirteen subcenters and eStroke platform.




