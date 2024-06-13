# tajijishui
YOLOv8分割检测

路径问题
项目代码全部使用绝对路径，使用时需修改路径

文件解析

|——.yolov8
|  |——.ViewCategory.py          #获取数据集标签类别与数量
|  |——.split.py                 #数据集划分比例
|  |——.json22txt.py             #把标签json文件转化为yolo所需的txt格式
|  |——.yolov8s-seg.pt           #加载预训练模型
|  |——.jishui_seg.yaml          #数据集训练验证的配置路径文件
|  |——.train.txt                #命令行指令
|  |——.runs                     #实验结果，仅保留了有效实验
|  |  |——.segment    
|  |  |  |——.train
|  |  |  |  |——.args.yaml       #训练实验的参数设置
|  |——.dataset                  #数据集
|  |——.ultralytics-main
|  |  |——.ultralytics
|  |  |  |——.cfg
|  |  |  |  |——.default.yaml    #修改各项参数




