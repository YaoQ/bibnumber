# Guide to compile the bibnumber and run it

Test bibnumber on Ubuntu 14.04

## Install dependencies and compile it
```
sudo apt-get install libopencv-dev libboost-dev tesseract-ocr libleptonica-dev libboost-filesystem-dev
make -C bibnumber/Debug
```

## Run example 
```
bibnumber/Debug/bibnumber -model samples/svm-prom1.xml samples/0009-IMG_0027.JPG
Read: [ 16 28 48]

```

