# VC_Assignment2
Folder with the dataset used for the second assignment of Computer Vision.

## Dataset structure

-> ANODE Dataset <-

The ANODE dataset was created in the context of the ATLANTIS project and contains 18230 images collected at the ATLANTIS Test Center in Viana do Castelo, more specifically at the DURIUS buoy, designed to test robotic platforms for O&M, and at the CRAS interior pool. The images depict Cathodic Protection Systems (CPSs), namely sacrificial anodes, which serve as a shield to protect a maritime structure from corrosion. This dataset serves to train Deep Learning object detectors. The ANODE dataset images were manually annotated and the correspondent labels are also available in txt files, one for each image. The txt files contain 5 values: the first correspondent to the object class and the other four to the bounding box information. These four values are normalized with respect to the image width and height (the top-left corner of the image is the origin):
- x coordinate center point of the bounding box;
- y coordinate center point of the bounding box;
- bounding box width;
- bounding box height.

The ANODE dataset folders are organized as follows:
- the robotic vehicle used for data collection, Kame or Fifish;
- the place where the data was collected, CRAS interior pool or DURIUS;
- the date when the testing campaign occurred in the format YEAR_MONTH_DAY;
- the type of data, images or labels.

The present repository contains the following items:
-> Fifish.zip - Folder containing the dataset images (in PNG format) and labels collected with the Fifish ROV;
-> Kame.zip - Folder containing the dataset images (in PNG format) and labels collected with the Kame ROV;
-> Sample.zip - Folder containing some images (in PNG format) and labels from the dataset.

Authors: João Dionísio, Pedro Nuno Leite, Andry Maykol Pinto
Contact information: joao.m.dionisio@inesctec.pt	

