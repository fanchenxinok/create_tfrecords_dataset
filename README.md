# create_tfrecords_dataset
创建tensorflow tfrecords数据集工具
原始图片数据的目录结构应该是：
     images/
           class1/
           class2/
           ...
           classn/
图片要求是jpg格式，每个类的图片放在对应的classn目录下。
用法如下：
  ./create_tfrecord.py --tfrecord_filename=images --dataset_dir=xxx/images/
