#Python第一周
##内建型态
- 内建型态所指的是内建在Python 直译器中，可以 直接撰写以建立实例的型态。
- Python的内建型态有三种，分别是: ▫ 数值型态(Numeric type)
- 字符串型态 (String type)
- 容器型态 (Container type)
##数值型态:
- 整数型态 (integer)
- 浮点数型态(float)
- 布尔型态(bool)
- 复数(complex)
##标准数据类型
###Python3 中有六个标准的数据类型：
- Number（数字）
- String（字符串）
- List（列表）
- Tuple（元组）
- Set（集合）
- Dictionary（字典）
- Python3 的六个标准数据类型中：
###不可变数据（3 个）：
1. Number（数字）
2. String（字符串）
3. Tuple（元组）；
###可变数据（3 个）：
1. List（列表）
2. Dictionary（字典）
3. Set（集合）
#List（列表）
List（列表） 是 Python 中使用最频繁的数据类型。
列表可以完成大多数集合类的数据结构实现。列表中元素的类型可以不相同，它支持数字，字符串甚至可以包含列表（所谓嵌套）。
列表是写在方括号 [] 之间、用逗号分隔开的元素列表。
和字符串一样，列表同样可以被索引和截取，列表被截取后返回一个包含所需元素的新列表。
- 列表截取的语法格式如下：
![](http://www.runoob.com/wp-content/uploads/2013/11/list_slicing1.png)
```python
#!/usr/bin/python3
 
list = [ 'abcd', 786 , 2.23, 'runoob', 70.2 ]
tinylist = [123, 'runoob']
 
print (list)            # 输出完整列表
print (list[0])         # 输出列表第一个元素
print (list[1:3])       # 从第二个开始输出到第三个元素
print (list[2:])        # 输出从第三个元素开始的所有元素
print (tinylist * 2)    # 输出两次列表
print (list + tinylist) # 连接列表
```
####注意：

1. List写在方括号之间，元素用逗号隔开。
2. 和字符串一样，list可以被索引和切片。
3. List可以使用+操作符进行拼接。
4. List中的元素是可以改变的。
Python 列表截取可以接收第三个参数，参数作用是截取的步长，以下实例在索引 1 到索引 4 的位置并设置为步长为 2（间隔一个位置）来截取字符串：
![](http://www.runoob.com/wp-content/uploads/2013/11/python_list_slice_2.png)
