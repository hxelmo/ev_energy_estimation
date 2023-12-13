# EV energy estimation

## 这是一个预测电动汽车（EV）的空调能量消耗的项目。
## 关于各个文件的任务目的：

### Data collection
get_data_from_db.ipynb 从数据库中部分天气数据和实际的EV的能量消耗数据
google_api_ele 通过Google Maps Elevation API取得道路的标高数据

### Data preprocessing
Prepare_dataset 将数据进行初步的统合，整理，以将数据转换成可用于机器学习模型训练的数据结构
Process_and_analyze_data 对整理好的数据集做进一步的分析和处理。比如检出和除外异常值

### Predictive model
测试了一些机器学习的算法。从结果上来看，随机森林是最适合的
