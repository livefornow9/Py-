## **2020.3.8** ##

### 列表是什么

- 用[]表示，用逗号分隔元素
```
lovefood = ['cheese','cake','milktea','doughnut','coffee']    ##注意str类型加‘’
lovenum = [3,5,6,8,9,0]
print(lovefood)
print(lovenum)

['cheese', 'cake', 'milktea', 'doughnut', 'coffee']
[3, 5, 6, 8, 9, 0]
```

### 如何访问列表

- 列表是有序的集合，因此访问需要给出该元素的位置或索引。
- 索引是从**0**开始的
```
lovefood = ['cheese','cake','milktea','doughnut','coffee']
lovenum = [3,5,6,8,9,0]
print(lovefood[0])
print(lovefood[3].title())
print(lovenum[5])

cheese
Doughnut
0
```
- 访问最后一个元素，使用[-1]
```
lovefood = ['cheese','cake','milktea','doughnut','coffee']
print(lovefood[-1])

coffee
```

- 使用列表中的值
```
lovefood = ['cheese','cake','milktea','doughnut','coffee']
message = ('my favorite food is '+lovefood[0]+' and '+lovefood[3]+' forever!')
message = "my favorite food is "+lovefood[0]+' and '+lovefood[3]+' '+"forever!"
print(message.title())

My Favorite Food Is Cheese And Doughnut Forever!
```


### 增删改
- 修改：**列表名[位序] = 新元素**
```
lovenum = [3,5,6,8,9,0]
print(lovenum)
lovenum[1] = 13
print(lovenum)

[3, 5, 6, 8, 9, 0]
[3, 13, 6, 8, 9, 0]
```

- 增加 

1.在列表末尾增加：**append(新元素)**
```
lovenum = [3,5,6,8,9]
lovenum.append(13)
print(lovenum)

[3, 5, 6, 8, 9, 13]
```

2.在列表中间增加：**insert(位序,新元素)**
```
lovenum = [3,5,6,8,9]
lovenum.insert(2,13)
print(lovenum)

[3, 5, 13, 6, 8, 9]
```


- 删除  
1.删除任意位置的元素：**del 表名[位序]**
```
lovenum = [3,5,6,8,9]
del lovenum[1]
print(lovenum)

[3, 6, 8, 9]
```
2.pop的使用：**弹出，并能接着使用该元素**
```
lovenum = [3,5,6,8,9]
lovenum.pop()
print(lovenum)

[3,5,6,8]

lovenum = [3,5,6,8,9]
lovenum.pop(1)
print(lovenum)

[3,6,8,9]
```
3.根据值删除元素
```
lovenum = [3,5,6,8,9]
lovenum.remove(5)       ##如果是删除字符，应该使用'单引号'
print(lovenum)

[3, 6, 8, 9]
```
ps：remove只删除第一个匹配的值，如果列表中有多个匹配值，需要用到**循环**，在后面会学习到


