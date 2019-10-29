# Object Detection Using ImageAI
Thanks ImageAI for the library

Built an object detection program with ImageAI

![picture alt](https://github.com/shubham769/OBJECT-DETECTION/blob/master/traffic_detect.jpeg)


To perform object detection using ImageAI, all you need to do is :
* Install Python on your computer system
* Install ImageAI and its dependencies
* Download the Object Detection model file
* Run the sample codes 

Now let’s get started.
* Download and install Python 3 from official Python Language website
 
 `https://python.org`

* Install the following dependencies via pip:

i. Tensorflow

`pip3 install tensorflow==1.12.0`

ii. Numpy

`pip3 install numpy`

iii. SciPy

`pip3 install scipy`

iv. OpenCV

`pip3 install opencv-python`

v. Pillow

`pip3 install pillow`

vi. Matplotlib

`pip3 install matplotlib`

vii. H5py

`pip3 install h5py`

viii. Keras

`pip3 install keras`

ix. ImageAI

`pip3 install imageai --upgrade`

* Download the RetinaNet model file that will be used for object detection via this link.
`https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5`

Thanks @OlafenwaMoses for this model

 Then place this model and the image you want to detect to the folder that contains the Object_detection python file.
* Execute the Object_detection.py file and wait for the result to the console like:

```ckpack  :  69.54809427261353 
motorcycle  :  51.88370943069458 
motorcycle  :  83.1535816192627 
person  :  66.27481579780579 
person  :  69.07155513763428 
person  :  79.24414873123169 
bicycle  :  64.439457654953 
bicycle  :  52.177244424819946 
person  :  86.37408018112183 
truck  :  76.61457061767578 
person  :  94.6185827255249 
bicycle  :  68.61521005630493 
bus  :  78.26051115989685```

* After that check the folder for the new generated file with object detected tags.
