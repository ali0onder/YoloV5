# YoloV5
This model is trained on a augmented image dataset of the video game Halo Infinite. Dataset contains screenshots of an online gameplay session. As a dataset made for object detection, the labels are enemy and enemy-head. Which is self explanatory itself. Model is trained by batches of 32 and for 15 epochs. Results are down below. Sudden spikes in validation losses could be an indication of overfitting. But the dataset size reached maximum (since it is vastly augmented at this point) so finding a model which has greatly better result than this model, could be doubtful.

![download](https://github.com/ali0onder/YoloV5/assets/129281448/27888c59-d0da-48a6-97d3-655d2eb059bc)

The original dataset is made by Graham Doerksen.
Dataset source: https://universe.roboflow.com/graham-doerksen/halo-infinite-angel-aim
