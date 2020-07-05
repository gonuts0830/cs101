## CS101 Lecture 1 Lab

### 欢迎来到计算机科学 101 的第一节实验课！

第一个练习！  
请在屏幕上打出“Hello World！” 向计算机世界问个好 :wink:

{% spoiler "提示" %}
请思考：该如何让计算机在屏幕上打印字符呢？
{% endspoiler %}

{% spoiler "答案" %}
print("hello world")
{% endspoiler %}

{% next "Exercise 2" %}

请用 PythonShell 来计算下面这个应用题：
假设你有一台可以复制金币的机器，如果放进去 20 枚金币每天最多就可以复制出 10 枚金币。现在已经有 20 枚金币了，问一年你最多会有多少金币？

{% spoiler "提示" %}  
python 运算符     

符号 | 运算
----- | -----
\+ | 加  
\- | 减  
\* | 乘  
/ | 除  
{% endspoiler %}

{% spoiler "答案" %}
\>>> 365 * 10    
3650    
\>>> 20 + 3650    
3670    
{% endspoiler %}


{% next "Exercise 3" %}

讨论：下列两个运算如果使用Python来运算有何不同？    
\>>> 5 + 7 * 5    
\>>> (5 + 7) * 5

下面两个算式结果一样么？    
\>>> 5 + 7 * 5 / 5    
\>>> ((5 + 7) * 5) / 5    

{% spoiler "答案" %}   
\>>> 5 + 7 * 5 / 5       
12.0   
\>>> ((5 + 7) * 5) / 5        
12.0     
  
思考：
1. 他们虽然结果一样，但是中间过程一样么？
2. 为什么python结果显示12.0 而不是12呢？

{% endspoiler %}

link: https://lab.cs50.io/gonuts0830/cs101/pythonSessionV202007/lecture1/