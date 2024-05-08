# Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## General Information
- The solution uses Convolutional Neural Network (CNN) to identify the type of class. To handle class imbalance, augmentor is also utilized.
- The model intially normalizes the input 0-255 to the range 0-1.
- Then a convolution layer (size=32) of kernel size (3,3) is used.
- Then a maxpooling layer (size=32) of  size (2,2) is used.
- Then a convolution layer (size=64) of kernel size (3,3) is used.
- Then a maxpooling layer (size=32) of  size (2,2) is used.
- Then a convolution layer (size=64) of kernel size (3,3) is used.
- Then a maxpooling layer (size=32) of  size (2,2) is used.
- Then flattening layer is used to convert to 1D array.
- Then a dense layer of 128 and finally softmax layer.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The initial validation dataset accuracy was 27% and after handling class imbalance using augmentor, the validataion dataset accuracy has increased to .

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Keras
- Tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project has been developed as part of Upgrad IIITB programme for AI and ML course's case study


## Contact
Created by [@josephmattamana90] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->