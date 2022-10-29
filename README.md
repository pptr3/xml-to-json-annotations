# Pascal VOC xml formato to COCO json format
This script converts annotations for Object Detectio from Pascal VOC xml format to COCO json format.

To be able to convert your xml annotations to json format, you need to provide three information:

1- all the labels within a list of string and assign the name `labels` to this list. Example:

`labels = ['Person', 'Car', 'Bicycle', 'Bus', 'Motorbike', 'Train', 'Aeroplane', 'Chair', 'Bottle', 'Dining', 'Table', 'Potted', 'Plant TV/Monitor', 'Sofa', 'Bird', 'Cat', 'Cow', 'Dog', 'Horse', 'Sheep']`

2- the path where all your xml files are present and name this variable `annpaths_list_path`. Example:

`annpaths_list_path = /home/pptr/annotaions/xml/`


3- where to save the created json file as long as its name.
Save this string into a variable named `annpaths_list_path`. Example:

`annpaths_list_path = /home/pptr/annotations/json/file.json`

Once filled these three variables, you can run the last cell of the notebook and get the work done.
