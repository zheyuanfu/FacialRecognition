# Facial Recognizer

The application can call the Facetime HD camera on MacBook to take pictures and display it on screen. After kicking the "process" button, the application can recognize facial expression of the people in picture and display it on screen.

# Features
The application provides functions for:
* Activate embedded camera on laptop
* Take picture of the user
* Show and save the picture taken
* Recognize the facial expression of user(using machine learning models including SVM or CNN)
* Show the recognition result on screen

My application can implement both CNN and SVM model(currently codes of CNN solution are commented because of duplicating). SVM method costs less time with lower accuracy while CNN costs more time with higher accuracy.

# Dependency
This application requires AVCaptureSession and AVCaptureConnection class

# Authors

Zheyuan Fu(zheyuanfu@gmail.com)

# Acknowledgments

Thanks to Hao Wu, Renqin Cai for helping with the implementation of CNN and SVM model respectively.


# 人脸表情识别应用
该应用可以使用Macbook端内置摄像头拍照，并且显示并保存照片。单击“process”按键后，该应用可以对照片上人物的表情进行识别并且将结果显示在桌面上。

# 功能
该应用包含以下功能：
* 开启终端机上的摄像功能
* 拍照
* 显示所拍摄的照片并保存
* 识别照片上人物的表情（使用机器学习的两种模型CNN和SVM）
* 显示处理结果

该应用可以实现CNN和SVM两种机器学习的模型（目前CNN方法的部分代码因为和SVM方法共享函数名已经做了注释）。 SVM方法耗时短但准确率较低，CNN方法耗时长但准确率较高。

# 依赖

该应用使用了AVCaptureSession和AVCaptureConnection类。


## 作者
傅哲渊（zheyuanfu@gmail.com）

##鸣谢
感谢Hao Wu和Renqin Cai对于本应用在CNN和SVM方面提供的帮助。



