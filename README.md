# Human-Detection-Deep-learnig-model-Faster-RCNN-
This is object detection project in which we detect a model(human) from images of a brand fashion shoots.The objective of this project is get human from image which is later on passed to other models for further processing.  

This code is executed on colab but you can execute it on your machine as well(windows and linux both).All you have to do is to change the format of annotate.txt.Linux and windows format are also provide in keras-frcnn\keras-frcnn-master\annotate.txt(files) folder.you have to change the file name as annotate.txt before running a model on windows or linux.

Some Key Points:

1- The format of train.csv should be:

   "filename,class_type,xmin,xmax,ymin,ymax"
   
2- annotate.txt is prepared from train.csv.

3- Format of annotate.txt should be(for colab project):

/content/drive/My Drive/keras-frcnn/keras-frcnn-master/train_images/img (70).jpg,human,222,574,17,1158

4- format of annotate.txt should be(for windows system):

C:\\Users\\DELL\\keras-frcnn\\keras-frcnn-master\\train_images\\img (358).jpg,human,30,800,244,1194

5- format of annotate.txt should be(for linix system):

//home//directory-Name//keras-frcnn//keras-frcnn-master//train_images//img(358).jpg,human,30,800,244,1194

Their are some path in train_frcnn.py and test_frcnn.py that you have to change before running the model otherwise you get error.

