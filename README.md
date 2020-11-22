# Python_basic
notes about python
#列表
l1 = [i for i in range(20)]#生成0-19的20个元素
print(l1)
print(l1[0:19])#索引从0开始，切片取到第二个索引值的前一位
print(l1[0:20])#想要取到最后一位，可以最大索引值+1
print(l1[1:-1])#用负数索引，同理取到索引值前一位
print(l1[:5])#如果左索引为0，可以省略0；右索引同理
print(l1[0:7:2])#第3个索引是步长
print(l1[::-1])#倒取所有元素
