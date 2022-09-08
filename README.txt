
To access Android Studio:

The directory contains the 'gradle.build' file used to build the modified example TensorFlow provides (TFDetect), and the file 'DetectorActivity.java' which is the responsible of performing the detection in the app. 

Requires TensorFlow API to be installed.

-------------------------------------

To access Jupyter Notebook 

1. Cd Object_Detection_Final_Project
2. Run: jupiter notebook
3. Opens at http://localhost:8888
3. Open: object_detection_tutorial-Copy3(img).ipynb 

------------------------------------

Information

Trained model frozen (exported) is: my_car_frozen_graph (frozen using chkpt 1000)

ssdlite_mobilenet_v2_coco_2018_05_09 is the original model selected and trained using test.record and train.record. Can view dataset CSV files.

training / ssd_mobilenet_v2_coco.config file contains the configuration prior to training (batch size, paths)


-------------------------
REFERENCES
-------------------------

ReadMe helped:
https://github.com/juandes/pikachu-detection

Tensorflow Object Detection API:
https://github.com/tensorflow/models/tree/master/research/object_detection

TFDetect:
https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android

Dataset:
https://github.com/udacity/self-driving-car/tree/master/annotations z

generate_tfrecord.py + xml_to_csv.py Scripts:
https://github.com/datitran/raccoon_dataset
