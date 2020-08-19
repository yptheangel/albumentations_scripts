# Albumentation Scripts
Scripts for albumentation to generate more image dataset for object detection.

### FYI
Currently support Pascal VOC object detction dataset only


### Setup
`pip install albumentations`<br>
`pip install jupyter`

### How to use
1. Run jupyter notebook server
2. Open up the notebooks and change the class list according to your dataset. List them in alphabetical order.
3. E.g. your classes are cat and dog. Apply <br>
`CLS=['cat','dog']`<br>
`category_id_to_name = {0:'cat',1:'dog'}`<br>
4. Change the path to your dataset
`datasetFolder=r'C:\Users\YOURusername\Desktop\YOURdatasetFolder'`
5. Run all