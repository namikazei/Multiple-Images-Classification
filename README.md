# Multiple-Images-Classification

TensorFlow Inception model is used to perform classification on number of images present in a directory.

## Prerequisite

To run this script you need to have Python and TensorFlow installed on your system


## How it works?

Once you have installed above prerequisites place all JPEG or JPG image files in img folder and run the script

```
python mul_classify_image.py

```
It will generate a result.txt file which consits of filenames, prediction labels and scores.

**Note: sample output for images present in img folder is shown below**

```
Filename: image_5.jpg
TensorFlow - Image Classification:
tiger, Panthera tigris - 78.537%
tiger cat - 9.822%
jaguar, panther, Panthera onca, Felis onca - 0.753%
lynx, catamount - 0.223%
leopard, Panthera pardus - 0.158%

Filename: image_1.jpg
TensorFlow - Image Classification:
meerkat, mierkat - 93.775%
mongoose - 1.971%
Windsor tie - 0.236%
black-footed ferret, ferret, Mustela nigripes - 0.060%
marmot - 0.031%

Filename: image_3.jpg
TensorFlow - Image Classification:
red fox, Vulpes vulpes - 91.107%
kit fox, Vulpes macrotis - 2.673%
grey fox, gray fox, Urocyon cinereoargenteus - 0.373%
dhole, Cuon alpinus - 0.177%
red wolf, maned wolf, Canis rufus, Canis niger - 0.167%

Filename: image_2.jpg
TensorFlow - Image Classification:
hyena, hyaena - 91.135%
African hunting dog, hyena dog, Cape hunting dog, Lycaon pictus - 1.869%
dhole, Cuon alpinus - 0.138%
dugong, Dugong dugon - 0.099%
custard apple - 0.035%

Filename: image_4.jpeg
TensorFlow - Image Classification:
tiger, Panthera tigris - 81.967%
tiger cat - 12.465%
zebra - 0.124%
jaguar, panther, Panthera onca, Felis onca - 0.074%
lynx, catamount - 0.055% 

```

## License

All files present in above folder are developed by TensorFlow authors. 
I have just added few lines of code and modified this classification script.
