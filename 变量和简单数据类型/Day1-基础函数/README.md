- title()  以首字母大写的方式显示每个单词

```
a = 'the stars in our planet'
print(a.title())
The Stars In Our Planet
```


- upper()  所有字母大写
```
a = 'the stars in our planet'
print(a.upper())
THE STARS IN OUR PLANET
```


- lower()  所有字母小写
```
a = 'THE STARS IN OUR PLANET'
print(a.upper())
the stars in our planet
```


- \+ 合并/拼接字符串
```
a = 'zhao'
b = 'xin'
print(a+b)
print(a+' '+b)        ##这里单引号中间有一个空格
zhaoxin
zhao xin
```


- 换行/添加空白
```
a = 'zhao'
b = 'xin'
print('\t'+a+'\n'+b)   ##\t表示tab 四个字符位，\n表示换行
	zhao
xin
```


- 删除空白
```
a = 'zhao    '
b = '    xin'
c = '    xin    '

print(a.rstrip())     ##删除右侧空白
print(b.lstrip())     ##删除左侧空白
print(c.strip())      ##删除两侧空白

zhao
xin
xin
```


- 数字
```
a=2
b=3
print(a+b)     ##在terminal可以直接输入2+3，回车
5
```
```
a = 23         ##此处你想要是数字int型，而python不知道你想要的是数字23还是字符2和3，所以会报错
message = ('happy '+ str(a) +'rd '+ 'birthday!')
print (message.title())
Happy 23Rd Birthday!
```



- python之禅
```
import this
```
The Zen of Python, by Tim Peters


Beautiful is better than ugly.   

Explicit is better than implicit.

Simple is better than complex.

Complex is better than complicated.

Flat is better than nested.

Sparse is better than dense.

Readability counts.

Special cases aren't special enough to break the rules.

Although practicality beats purity.

Errors should never pass silently.

Unless explicitly silenced.

In the face of ambiguity, refuse the temptation to guess.

There should be one-- and preferably only one --obvious way to do it.

Although that way may not be obvious at first unless you're Dutch.

Now is better than never.

Although never is often better than *right* now.

If the implementation is hard to explain, it's a bad idea.

If the implementation is easy to explain, it may be a good idea.

Namespaces are one honking great idea -- let's do more of those!



