# 重点

    1.项目启动较慢等待2-7秒
    2.启动摄像头后需要等待5-10秒，并不能对窗口进行任何操作，不然会出现响应的情况
    3.如果操作不当情况关闭窗口重新打开即可    

# 搭配环境

    *** python环境 ***
        1.3.10及以上
    
    *** 安装opencv依赖包 ***
        1.pip install opencv-python
    
    *** 容易报错 ***
        1.haarcascade_frontalface_default.xml和openCvGui必须相对目录
        2.目录csvs,目录images,目录images_tuxiang不能删除
        3.不能对目录名和文件名进行修改和更改位置，不然容易报错
    
    *** 项目使用依赖包 ***
        import csv
        import os
        import random
        import sys
        import time
        from datetime import datetime
        from tkinter import *
        from tkinter import messagebox, filedialog
        from tkinter.ttk import Treeview
        import tkinter as tk
        from PIL import ImageTk, Image
        import cv2

# 功能介绍
    1.利用cv2可以获取本机摄像头
    2.获取的摄像头可以进行人脸识别
    3.可以对识别处来的图像保存处理
    4.可以利用访问本机目录获取PNG,JPG,JPEG格式的图片文件
    5.可以对本机目录访问的图片人脸识别
    6.可以对本机目录访问的图片人脸识别以及可以保存

# 更新项目
    官网:http://yilingjiu.top
    Github:Github: https://github.com/YLJ109/OpenCvGui/

# 联系
    邮箱:2869563610@qq.com