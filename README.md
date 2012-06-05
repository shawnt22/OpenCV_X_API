OpenCV_X_API
============

OpenCV X API for Objective-C

Copyright shawnt22@gmail.com. All rights received.

Setup OpenCV library
============

1.  Copy OpenCV folder to project root folder.

    boost : you can download from https://github.com/BloodAxe/opencv-ios-template-project/tree/master/externalLibs/boost
    opencv-build-ios-7599 : you can download from http://computer-vision-talks.com/download/opencv-build-ios-7599.zip

2.  Add Header Search Paths

    $(SRCROOT)/OpenCV/boost/include
    $(SRCROOT)/OpenCV/opencv-build-ios-7599/include

3.  Add Library Search Paths

    Debug : $(SRCROOT)/OpenCV/opencv-build-ios-7599/lib/Debug
    Release : $(SRCROOT)/OpenCV/opencv-build-ios-7599/lib/Release

4.  Add Other Linker Flags

    -lopencv_contrib    -lopencv_features2d   -lopencv_flann
    -lopencv_calib3d    -lopencv_imgproc      -lopencv_legacy
    -lopencv_core       -lopencv_ml           -lopencv_objdetect
    -lopencv_video      -lzlib