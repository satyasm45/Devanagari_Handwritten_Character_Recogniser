The project aims to classify the Devanagri Handwritten Character Data Set into 46 classes. The dataset can be found from here
https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset

The dataset included 92000 32*32 grey scaled images.

The inspiration for this project comes from other open-source implementations and documentation.

The data_preparation notebook has also been added which includes simple techniques to correctly form the X_train,X_test,Y_train,Y_test
files along with a reference dictionary for all the 46 classes of characters. Further in the Recogniser X_val was also formed.

The training was done using Google Colaboratory's default GPU support.

The Model_plot can be also be found as a PNG file.

The proposed model has an accuracy of 97.68%.