# Kitti-processing
Scripts for using Kitti Data Set

To download the dataset from the archive use : 
```
wget -i download_script.txt -P ~/output_folder/
```

To convert the png files to jpg for saving memory after extracting : 
```
find ~/output_folder/ -name '*.png' | parallel 'convert {.}.png {.}.jpg && rm {}'
```
Splits common for monocular training: [Zhou's subset](https://github.com/tinghuiz/SfMLearner)

