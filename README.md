#Robot-Competition

## 比赛分为3轮进行
 -	第一轮：纯色块目标识别；
 -	第二轮：纯实物照片识别；
 -	第三轮：实物与色块混合识别。
 
三轮比赛成绩相加进行最终排名。

## 任务分工
 姜瑞： 主要完成opencv的内容  
 董世佛： 完成qt的内容，辅助opencv识别

## 时间
7.21开始  
<font color=red>8.10以前需要基本完成。</font>

## 第一轮任务
识别在板上的色块：只限圆形、正方形、长方形、椭圆形4种（ID依次为1, 2, 3, 4）；


## 一般程序的编译方法：
g++ main.cpp -o main `pkg-config --cflags --libs opencv`
./main test.jpg

