# 75000-Rice-Image-Dataset-for-Object-Detection-and-Object-Segmentation

## Intro
Rice is the seed of the grass species Oryza sativa or less commonly Oryza glaberrima. The name wild rice is usually used for species of the genera Zizania and Porteresia, both wild and domesticated, although the term may also be used for primitive or uncultivated varieties of Oryza.

### Popular Types of Rice
1. Basmati Rice
2. Jasmine Rice
3. Wild Rice
4. Calrose Rice
5. Japanese Short-Grain Rice (uruchimai 粳米)
6. Sushi Rice
7. Japanese Glutinous (Sticky) Rice
8. Arborio Rice 
9. Black Rice
10. Medium-Grain Brown Rice
11. Valencia Rice
12. Red Rice
13. Rice Blends
14. Parboiled Rice

## About The Original Data
The images were originally published by [Murat Koklu](https://www.kaggle.com/muratkokludataset) on [Kaggle](https://www.kaggle.com/) under a [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) licence. You can find the images using the following link [Rice Image Dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset).

The original data contains images of 5 Different Types of Rice and each type contains 15000 images bringing the total to 75000. 

## About the Annotated Data
For Preparing the Images for Object Detection and Object Segmentation, An Automatic Annotator Script was developed in Python. Because the annotations were created Automatically, they have a High Degree of Accuracy.

The Annotations are in [LabelMe](https://github.com/wkentaro/labelme) [JSON](https://www.json.org/json-en.html) format. Annotation JSONs also contain the encoded version of the images that can be used to recreate the images if the need arise. 

## Tests Done
A few tests were also done using the annotated images. For one of the tests, A Small Version of [YOLOv5](https://github.com/ultralytics/yolov5) Object Detection Model was selected. For this test, The Basmati Rice Images were combined in grids of 4 * 4 which brought the total sum of the images, approximately, to around 900. 
The batch size of the model was 12 and it was trained for 20 Epochs. 



## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

This implies that you are free to do everything as long as you mention the author properly. For more information please check the LICENSE. 



