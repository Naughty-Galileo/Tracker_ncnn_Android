# Tracker-ncnn
This project is a ncnn Android demo for SOT Tracker(LightTrack...), it depends on ncnn library and opencv.  
fork from https://github.com/FeiGeChuanShu/ncnn_Android_LightTrack.git 
 
## how to build and run  
### step1  
https://github.com/Tencent/ncnn/releases

* Download ncnn-YYYYMMDD-android-vulkan.zip or build ncnn for android yourself
* Extract ncnn-YYYYMMDD-android-vulkan.zip into **app/src/main/jni** and change the **ncnn_DIR** path to yours in **app/src/main/jni/CMakeLists.txt**

### step2  
https://github.com/nihui/opencv-mobile  

* Download opencv-mobile-XYZ-android.zip
* Extract opencv-mobile-XYZ-android.zip into **app/src/main/jni** and change the **OpenCV_DIR** path to yours in **app/src/main/jni/CMakeLists.txt**

### step3
* Open this project with Android Studio, build it and enjoy!  


## Reference  
1.https://github.com/researchmm/LightTrack  
2.https://github.com/Tencent/ncnn  
3.https://github.com/FeiGeChuanShu/ncnn_Android_LightTrack.git
