# ShipDetection
Classification of different categories of ships
* Ship or vessel detection has a wide range of applications, in the areas of maritime safety,  fisheries management, marine pollution, defence and maritime security, protection from piracy, illegal migration, etc.
* Keeping this in mind, this is a computer vision based project to identify ship type only from the images taken by the survey boats.
* Used transfer learning for this ships classification.

## Prerequisites
* Run SD.ipynb in collab notebook.

## Dataset Description
* There are 6252 images in train and 2680 images in test data. The categories of ships and their corresponding codes in the dataset are as
{'Cargo': 1, 
'Military': 2, 
'Carrier': 3, 
'Cruise': 4, 
'Tankers': 5}
* The files train.zip, test.csv have structure as 

  Name of the image in the dataset (ID column), Ship category code
* train.zip contains the images corresponding to both train and test set along with the true labels for train set images in train.csv and for test set images in test.csv

## References
* Dataset is taken from Analytical Vidhya compitition
