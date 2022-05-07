详细添加方法：https://blog.csdn.net/weixin_50008473/article/details/124590939?spm=1001.2014.3001.5501  
本文YOLOV5为6.1版本
主要步骤：
（1）models/common.py中注册注意力模块
（2）models/yolo.py中的parse_model函数中添加注意力模块
（3）修改配置文件yolov5s.yaml
（4）运行yolo.py进行验证
