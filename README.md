
# Multi Modality Medical Image Translation for Dicom Brain Images


The acquisition time for different MRI (Magnetic Resonance Imaging) image modalities pose a unique challenge to the efficient usage of the contemporary radiology technologies. The ability to synthesize one modality
from another can benefit the diagnostic utility of the scans. Currently, all the exploration in the field of medical image to image translation is focused on NIfTI (Neuroimaging Informatics Technology Initiative) images.
However, DICOM (Bidgood et al., 1997) images are the prevalent image standard in MRI centers. Here,
we propose a modified deep learning network based on U-Net architecture for T1-Weighted image (T1WI)
modality to T2-Weighted image (T2WI) modality image to image translation for DICOM images and vice
versa. Our deep learning model exploits the pixel wise features between T1W images and T2W images which
are important to understand the brain structures. The observations indicate better performance of our approach
to the previous state-of-the-art methods. Our approach can help to decrease the acquisition time required for
the scans and thus, also avoid motion artifacts.





## Dataset

We got the dataset from an MRI Imaging Center solely for research purpose.

The dataset acquired in order to carry out the evaluation consisted of paired T1W and T2W images for
21 subjects. Per subject 18 axial slices were available
from segregated brain scans. The data was split into a
training set of 90 slices and a testing set of 36 slices.


## Screenshots

![Modified UNET ](https://github.com/yashvimalu/Medical-Image-Translation-Brain-MRI-Dicom-Images/blob/main/Final%20Unet.jpg)

![T1 to T2 Output ](https://github.com/yashvimalu/Medical-Image-Translation-Brain-MRI-Dicom-Images/blob/main/T1%20to%20T2.jpg)

![T2 to T1 Output ](https://github.com/yashvimalu/Medical-Image-Translation-Brain-MRI-Dicom-Images/blob/main/T2%20to%20T1.jpg)


## Authors

- [@yashvimalu](https://github.com/yashvimalu)
- [@Dhyey-Nikalwala](https://github.com/Dhyey-Nikalwala)
- [@urmi6899](https://github.com/urmi6899)
- Jinal Patel
- Ninad Anklesaria
- Dr. Nirali Nanavati
- Preethi Srinivasan
-  Arnav Bhavsar

## Paper

https://www.scitepress.org/PublicationsDetail.aspx?ID=31VvJZqo8uo=&t=1
