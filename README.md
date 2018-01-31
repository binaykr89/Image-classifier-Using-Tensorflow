# Image-classifier-Using-Tensorflow


Congratulations !! You reached here..

Training
python C:/Users/BINAY/tensorflow-for-poets-2/scripts/retrain.py \ --bottleneck_dir=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/bottlenecks \ --how_many_training_steps=600 \ --model_dir=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/models/"${ARCHITECTURE}" \ --summaries_dir=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/training_summaries/"${ARCHITECTURE}" \ --output_graph=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/retrained_graph.pb \ --output_labels=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/retrained_labels.txt \ --image_dir=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/flower_photos

Inference
python  C:/Users/BINAY/tensorflow-for-poets-2/scripts/label_image.py --graph=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/retrained_graph.pb --image=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/flower_photos/daisy/21652746_cc379e0eea_m.jpg

python  C:/Users/BINAY/tensorflow-for-poets-2/scripts/label_image.py --graph=C:/Users/BINAY/tensorflow-for-poets-2/tf_files/retrained_graph.pb --image=C:/Users/BINAY/Desktop/Rainbow-colored-beautiful-rose-37074104.jpg



* For [TensorFlow Lite](https://www.tensorflow.org/mobile/tflite/) the new, ground up rewrite targeted at mobile devices
  use [this version of the codelab](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets-2-tflite) 
* For the more mature [TensorFlow Mobile](https://www.tensorflow.org/mobile/mobile_intro) use 
  [this version of the codealab](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets-2).
