# TensorFlow2_Object_Detection_PTM
This repo will help to build a object detection model in real time using pre-trained-models.

Labeling the Image you have download this git hub repostries:https://github.com/tzutalin/labelImg
And type this command to install certain packages
  * conda install pyqt=5
  * conda install -c anaconda lxml
After successfully installing packages you have type this command from LabelImg location
  * pyrcc5 -o resource.py resource.qrc #This command is to convert image into xml file
Then you have to open your file explore copy the resource.py and resource.qrc and then paste it in libs which will be there in labelImg folder
After that open cmd type python labelImg.py
labelmg API will display label your Image .

For installing Tensorflow2 Object Detection Please follow this link:https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html#tensorflow-object-detection-api-installation

In this link they are given very clearly how to install TFOD2 dependencies.

After completing all these step you can develop your own objection detection model using pre-trained-model in this project I have used ssd_mobilenet_v2_fpnlite_320x320_coco17_tpu-8