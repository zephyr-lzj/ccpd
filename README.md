# ccpd
- 是什么？
  - "CCPD" 数据集通常指的是"Chinese City Parking Dataset"，即中文城市停车数据集。这是一个用于计算机视觉和车辆识别任务的数据集，主要用于训练和评估算法在车辆检测、车牌识别等方面的性能。
- 原始数据集格式
  - json
 
# 数据集文件夹结构
- json
'''
dataset/
|-- images/
|   |-- image1.jpg
|   |-- image2.jpg
|   |-- ...
|-- annotations/
|   |-- annotation1.json
|   |-- annotation2.json
|   |-- ...
|-- classes.txt

'''

- yolo
'''
dataset/
|-- images/
|   |-- image1.jpg
|   |-- image2.jpg
|   |-- ...
|-- labels/
|   |-- image1.txt
|   |-- image2.txt
|   |-- ...
|-- classes.txt

'''


# 我做了什么？
- 把json格式转化为yolo格式
