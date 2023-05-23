# -Python---
2023/4 - 2023/5, 利用Python学习数据分析笔记
## Numpy
>特点：矩阵计算，摆脱循环，高性能低内存  
>>import Numpy as np  
>>学习 **第04章 NumPy基础：数组和矢量计算**
* 生成数组：data = np.array([[1,2,3],[4,5,6]])  
* 生产0~(n-1)数组 data = np.arange(n)  
* 生成(n,m)的正态分布随机数矩阵: data = np.random.randn(n,m)  
* 广播，线性代数
## pandas
> 特点：表格操作，时间序列，索引，过滤，清洗，插值，数据聚合，数据分块  
>> 数据类型：Series，DataFrame  
>> 学习 **第05章 pandas入门**
* Series  
  * data = np.Series(数据)
  * 只有 Index，且可以修改   
  * 可以索引  
* DataFrame  
  * data = np.DataFrame(表)  
  * 竖着的是columns，横着的是index，可以修改  
* 索引  
  * Data[0] 索引第一行  
  * iloc 整数位置索引  
    > data.iloc[0] 选取第一行  
    > data.iloc[0,[0,1]] 选取第一行的第一列和第二列  
  * loc 标签索引  
    > data.loc['Colorado', ['two', 'three']]  
 
## matplotlib:
>特点：制图
>>不如直接去官网学

