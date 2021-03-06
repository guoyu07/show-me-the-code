## Python 练习册

#### 题目来源：####

- 前 23 题(不包括 0022 题)来自 MOOC 哈工大 @carfly 车万翔老师 OJ 作业题。
- 第 0022 和 0058 题来自[Yixiaohan/show-me-the-code](https://github.com/Yixiaohan/show-me-the-code), 具体题号已在题目中标注。
- 第 0023 题后面的题目来自 [Think Python](http://www.greenteapress.com/thinkpython/) 章节练习题

----------

**第 0000 题：**提交 Python 程序，将 Hello World 两个单词分别输出到相邻的两行。（注意：每个单词后面没有空格）

**第 0001 题：**身体质量指数（Body Mass Index，BMI）是根据人的体重和身高计算得出的一个数字，BMI对大多数人来说，是相当可靠的身体肥胖指标，其计算公式为：BMI = Weight/High^2，其中体重单位为公斤，身高单位为米。编写程序，提示用户输入体重和身高的数字，输出BMI。

**第 0002 题：**接收用户输入的一个秒数（非负整数），折合成小时、分钟和秒输出。

**第 0003 题：**对于三角形，三边长分别为a, b, c，给定a和b之间的夹角C，则有：c^2 = a^2+b^2-2axbxcos(C)。编写程序，使得输入三角形的边a, b, c，可求得夹角C(角度值)。

**第 0004 题：**如果列出10以内自然数中3或5的倍数，则包括3,5,6,9。那么这些数字的和为23。要求计算得出任意正整数n以内中3或5的倍数的自然数之和。

**第 0005 题：**10以内的素数2,3,5,7的和为17。要求计算得出任意正整数n以内的所有素数的和。

**第 0006 题：**根据下列信息计算在1901年1月1日至2000年12月31日间共有多少个星期天落在每月的第一天上？

- a)  1900.1.1是星期一
- b)  1月，3月，5月，7月，8月，10月和12月是31天
- c)  4月，6月，9月和11月是30天
- d)  2月是28天，在闰年是29天
- e)  公元年数能被4整除且又不能被100整除是闰年
- f)  能直接被400整除也是闰年

**第 0007 题：**数字197可以被称为循环素数，因为197的三个数位循环移位后的数字：197,971,719均为素数。100以内这样的数字包括13个，2,3,5,7,11,13,17,31,37,71,73,79,97。要求任意正整数n以内一共有多少个这样的循环素数。

**第 0008 题：**一个斐波那契数列的前10项为：1, 2, 3, 5, 8, 13, 21, 34, 55, 89，对于一个最大项的值不超过n的斐波那契数列，求值为偶数的项的和。

**第 0009 题：**若已知1800年1月1日为星期3，则对于一个给定的年份和月份，输出这个月的最后一天是星期几。

**第 0010 题：**如在汉诺塔游戏中，我们希望将塔A上的n个盘子，通过塔B移动到塔C，则对于任意输入的n，给出移动的步骤。

**第 0011 题：**“Pig Latin”是一个英语儿童文字改写游戏。

整个游戏遵从下述规则：

(1). 元音字母是‘a’、‘e’、‘i’、‘o’、‘u’。字母‘y’在不是第一个字母的情况下，也被视作元音字母。其他字母均为辅音字母。例如，单词“yearly”有三个元音字母（分别为‘e’、‘a’和最后一个‘y’）和三个辅音字母（第一个‘y’、‘r’和‘l’）。

(2). 如果英文单词以元音字母开始，则在单词末尾加入“hay”后得到“Pig Latin”对应单词。例如，“ask”变为“askhay”，“use”变为“usehay”。

(3). 如果英文单词以‘q’字母开始，并且后面有个字母‘u’，将“qu”移动到单词末尾加入“ay”后得到“Pig Latin”对应单词。例如，“quiet”变为“ietquay”，“quay”变为“ayquay”。

(4). 如果英文单词以辅音字母开始，所有连续的辅音字母一起移动到单词末尾加入“ay”后得到“Pig Latin”对应单词。例如，“tomato”变为“omatotay”， “school” 变为“oolschay”，“you” 变为“ouyay”，“my” 变为“ymay ”，“ssssh” 变为“sssshay”。

(5). 如果英文单词中有大写字母，必须所有字母均转换为小写。 

**第 0012 题：**依次判断一系列给定的字符串是否为合法的 Python 标识符。

**第 0013 题：**依次计算一系列给定字符串的字母值，字母值为字符串中每个字母对应的编号值（A对应1，B对应2，以此类推，不区分大小写字母，非字母字符对应的值为0）的总和。例如，Colin 的字母值为 3 + 15 + 12 + 9 + 14 = 53

**第 0014 题：**定义一个 prime() 函数求整数 n 以内（不包括n）的所有素数（1不是素数），并返回一个按照升序排列的素数列表。使用递归来实现一个二分查找算法函数bi_search()，该函数实现检索任意一个整数在 prime() 函数生成的素数列表中位置（索引）的功能，并返回该位置的索引值，若该数不存在则返回 -1。

**第 0015 题：**帕斯卡三角形，又称杨辉三角形是二项式系数在三角形中的一种几何排列。帕斯卡三角形通常从第0行开始枚举，并且每一行的数字是上一行相邻两个数字的和。在第0行只写一个数字1，然后构造下一行的元素。将上一行中数字左侧上方和右侧上方的数值相加。如果左侧上方或者右侧上方的数字不存在，用0替代。下面给出6行的帕斯卡三角形：

```
     1
    1 1
   1 2 1
  1 3 3 1
 1 4 6 4 1
1 5 10 10 5 1
```
编写程序，输入帕斯卡三角形的高度 n，然后生成和上面例子一样风格的三角形。

**第 0016 题：**倒排索引（Inverted index），也常被称为反向索引，是一种索引方法，用来存储某个单词存在于哪些文档之中。是信息检索系统中最常用的数据结构。通过倒排索引，可以根据单词快速获取包含这个单词的文档列表。

![](http://ww4.sinaimg.cn/large/8178ba0ejw1epo6rz23fwj20ru0kk0xh.jpg)

本作业主要完成以下四个功能：

(1). 建立索引：首先输入100行字符串，用于构建倒排索引，每行字符串由若干不含标点符号的、全部小写字母组成的单词构成，每个单词之间以空格分隔。依次读入每个单词，并组成一个由<单词, 每个单词出现的行号集合>构成的字典，其中行号从1开始计数。

(2). 打印索引：按照字母表顺序依次输出每个单词及其出现的位置，每个单词出现的位置则按行号升序输出。例如，如果“created”出现在第3, 20行，“dead”分别出现在14, 20, 22行。则输出结果如下（冒号和逗号后面都有一个空格，行号不重复）：

    …
    created: 3, 20
    dead: 14, 20, 22
    …

(3). 检索：接下来输入查询(Query)字符串，每行包含一个查询，每个查询由若干关键字(Keywords)组成，每个关键字用空格分隔且全部为小写字母单词。要求输出包含全部单词行的行号（升序排列），每个查询输出一行。若某一关键字在全部行中从没出现过或没有一行字符串包含全部关键字，则输出“None”。遇到空行表示查询输入结束。如对于上面创建的索引，当查询为“created”时，输出为“3, 20”；当查询为“created dead”时，输出为“20”；当查询为“abcde dead”时，输出为“None”；

(4). 高级检索：当输入的Query以“AND: ”开始，则执行“与”检索，即要求输出包含全部关键字的行；如果输入的Query以“OR:”开始，则执行“或”检索，即某行只要出现了一个关键字就满足条件。默认情况（不以“AND: ”或“OR: ”开始），执行“与”检索。

**输入格式:**

首先输入100行字符串，每行字符串由若干不含标点符号的、全部小写字母组成的单词构成，每个单词之间以空格分隔。
若干个查询，每个查询占一行，既可能是普通检索，也可能是高级检索。

**输出格式：**

首先打印索引，然后将每个查询的结果输出到一行。

**第 0017 题：**实现逆向最大匹配分词算法，即从右向左扫描，找到最长的词并切分。如句子“研究生命的起源”，逆向最大匹配分词算法的输出结果为“研究 生命 的 起源”。

**输入格式:**

第一行是以utf-8格式输入的词表，每个词之间以空格分隔。
接下来是若干行以utf-8格式输入的中文句子。

**输出格式：**

以utf-8格式输出的逆向最大匹配的分词结果，每个词之间使用空格分隔。每个输入对应一行输出。

**输入样例：**

你 我 他 爱 北京 天安门 研究 研究生 命 生命 的 起源
研究生命的起源
我爱北京天安门

**输出样例：**

研究 生命 的 起源
我 爱 北京 天安门

**第 0018 题：**两位整数相乘形成的最大回文数是 9009 = 99 × 91。编写程序，求得任意输入的 n 位整数相乘形成的最大回文数。

**输入格式:**
正整数 n 
 
**输出格式：**
n 位整数相乘形成的最大回文数
 
**输入样例：**
2
 
**输出样例：**
9009

**第 0019 题：**用 Tkinter 写一个如图的 GUI 程序，要求单击按钮能改变文本的颜色和边界形式，按键盘方向键画布上的图形能改变大小。

![](http://ww1.sinaimg.cn/large/8178ba0egw1eojroehdo1j208v0brwer.jpg)

**第 0020 题：**建立 splite 数据库，创建 student 表格，表格中有以下数据

id  | name   | room  | tel     
--- | ------ | ----- | --------      
666 | zhan   | 6-303 | 83272451 
777 | zhang  | 6-404 | 83423567 
888 | zhuang | 6-505 | 83256673 

在 Python 中使用 sqlite，并且实现参数化查询，即当输入一个 name 时，显示 name 的相关信息。

**第 0021 题：**用 Django Web 开发框架搭建一个本地的 Web 站点并且编写 Django 应用，在不同 url  下完成以下功能：

1. `/hello` 对任意 Request 返回 "Hello world"
2. `/time`  运用模板动态显示 "现在的时间是..."
3. `/insert` 创建模型，安装数据库，以表单的形式要求用户填入联系人的 name, sex, phone, email, address 并且在 Python 中获得输入的内容插入于数据库中
4. `/list` 在网页上显示联系人信息

**第 0022 题：**任一个英文的纯文本文件，统计其中的单词出现的个数。via [Yixiaohan/show-me-the-code 第 0004 题](https://github.com/Yixiaohan/show-me-the-code)

**第 0023 题：**遍历 names.txt 文件，输出长度最长的回文人名。

**第 0024 题：**Write a function that draws a grid like the following:

```
+ - - - -  + - - - -  +
|          |          |
|          |          |
|          |          |
|          |          |
+ - - - -  + - - - -  +
|          |          |
|          |          |
|          |          |
|          |          |
+ - - - -  + - - - -  +
```

And write a function that draws a similar grid with four rows and four  columns.

**第 0025 题：**用 Swampy 包中的 TurtleWorld 模块画如图所示的花的形状。
![](http://ww2.sinaimg.cn/large/8178ba0ejw1epob9bvgwkg20b90b6465.gif)

**第 0026 题：**Fermat’s Last Theorem says that there are no integers a, b, and c such that

![](http://ww1.sinaimg.cn/large/8178ba0egw1eow35k15suj20ju02tdfp.jpg)

- Write a function named `check_fermat` that takes four parameters—a, b, c and n—and that checks to see if Fermat’s theorem holds. If n is greater than 2 and it turns out to be true that

![](http://ww1.sinaimg.cn/large/8178ba0egw1eow36kxcmrj20je01kq2p.jpg)

the program should print, “Holy smokes, Fermat was wrong!” Otherwise the program should print, “No, that doesn’t work.”

- Write a function that prompts the user to input values for a, b, c and n, converts them to integers, and uses check_fermat to check whether they violate Fermat’s theorem.

**第 0027 题：**If any of the three lengths is greater than the sum of the other two, then you cannot form a triangle. Otherwise, you can. 

1. Write a function named `is_triangle` that takes three integers as arguments,and that prints either “Yes” or “No,” depending on whether you can or cannot form a triangle from sticks with the given lengths.
2. Write a function that prompts the user to input three stick lengths, converts them to integers, and uses `is_triangle` to check whether sticks with the given lengths can form a triangle.

**第 0028 题：**The Koch curve is a fractal that looks something like Figure.

![](http://ww3.sinaimg.cn/large/8178ba0ejw1eowd9sie65j20jr049jrd.jpg)

To draw a Koch curve with length x, all you have to do is

1. Draw a Koch curve with length x/3. 
2. Turn left 60 degrees.
3. Draw a Koch curve with length x/3.
4. Turn right 120 degrees.
5. Draw a Koch curve with length x/3.
6. Turn left 60 degrees.
7. Draw a Koch curve with length x/3.

The exception is if x is less than 3: in that case, you can just draw a straight line with length x.

1. Write a function called `koch` that takes a turtle and a length as parameters, and that uses the
turtle to draw a Koch curve with the given length.
2. Write a function called `snowflake` that draws three Koch curves to make the outline of a snowflake.

![](http://ww1.sinaimg.cn/large/8178ba0ejw1epobtqyf10g20b90b6avq.gif)

**第 0029 题：**The Ackermann function, A(m, n), is defined:

![](http://ww4.sinaimg.cn/large/8178ba0ejw1eowjour35sj20jq03i0sr.jpg)

Write a function named ack that evaluates Ackermann’s function. Use your function to evaluate ack(3, 4), which should be 125. What happens for larger values of m and n?

**第 0030 题：**A palindrome is a word that is spelled the same backward and forward, like “noon” and “redivider”. **Recursively**, a word is a palindrome if the first and last letters are the same and the middle is a palindrome.

Write a function called `is_palindrome` that takes a string argument and returns True if it is a palindrome and False otherwise.

**第 0031 题：**The greatest common divisor (GCD) of a and b is the largest number that divides both of them with no remainder.

One way to find the GCD of two numbers is Euclid’s algorithm, which is based on the observation that if r is the remainder when a is divided by b, then gcd(a, b) = gcd(b, r). As a base case, we can use gcd(a, 0) = a.

Write a function called gcd that takes parameters a and b and returns their greatest common divisor.

Credit: This exercise is based on an example from Abelson and Sussman’s Structure and Interpre- tation of Computer Programs.

**第 0032 题：**The built-in function eval takes a string and evaluates it using the Python interpreter. For example:

```
>>> eval('1 + 2 * 3')
7
>>> import math
>>> eval('math.sqrt(5)')
2.2360679774997898
>>> eval('type(math.pi)')
<type 'float'>
```

Write a function called `eval_loop` that iteratively prompts the user, takes the resulting input and evaluates it using eval, and prints the result.

It should continue until the user enters 'done', and then return the value of the last expression it evaluated.

**第 0033 题：**Write a function `square_root` using Newton's method.

To test the square root algorithm in this chapter, you could compare it with math.sqrt. Write a function named `test_square_root` that prints a table like this:

![](http://ww1.sinaimg.cn/large/8178ba0ejw1eoxe7st1m7j20jx06rq3o.jpg)

The first column is a number, a; the second column is the square root of a computed with the function `square_root`; the third column is the square root computed by `math.sqrt`; the fourth column is the absolute value of the difference between the two estimates.

**第 0034 题：**The mathematician Srinivasa Ramanujan found an infinite series that can be used to generate a numerical approximation of π:

![](http://ww4.sinaimg.cn/large/8178ba0ejw1eoxgcpyz8bj20jy02hdfs.jpg)

Write a function called `estimate_pi` that uses this formula to compute and return an estimate of π. It should use a while loop to compute terms of the summation until the last term is smaller than 1e-15 (which is Python notation for 10−15). You can check the result by comparing it to math.pi.

**第 0035 题：**ROT13 is a weak form of encryption that involves “rotating” each letter in a word by 13 places. To rotate a letter means to shift it through the alphabet, wrapping around to the beginning if necessary, so ’A’ shifted by 3 is ’D’ and ’Z’ shifted by 1 is ’A’.

Write a function called `rotate_word` that takes a string and an integer as parameters, and that returns a new string that contains the letters from the original string “rotated” by the given amount.

For example, “cheer” rotated by 7 is “jolly” and “melon” rotated by -10 is “cubed”.

You might want to use the built-in functions ord, which converts a character to a numeric code, and chr, which converts numeric codes to characters.

Potentially offensive jokes on the Internet are sometimes encoded in ROT13.

**第 0036 题：**Write a function called `nested_sum` that takes a nested list of integers and add up the elements from all of the nested lists.

**第 0037 题：**write a function named `capitalize_nested` that takes a nested list of strings and returns a new nested list with all strings capitalized.

**第 0038 题：**The (so-called) Birthday Paradox:

1. Write a function called `has_duplicates` that takes a list and returns True if there is any element that appears more than once. It should not modify the original list.

2. If there are 23 students in your class, what are the chances that two of you have the same birthday? You can estimate this probability by generating random samples of 23 birthdays and checking for matches. Hint: you can generate random birthdays with the randint function in the random module.

**第 0039 题：**Write a function that reads the file words.txt and builds a list with one element per word. Write two versions of this function, one using the append method and the other using the idiom t = t + [x]. Which one takes longer to run? Why?

Hint: use the time module to measure elapsed time.

**第 0040 题：**To check whether a word is in the word list, you could use the in operator, but it would be slow because it searches through the words in order.

Because the words are in alphabetical order, we can speed things up with a bisection search (also known as binary search), which is similar to what you do when you look a word up in the dictionary. You start in the middle and check to see whether the word you are looking for comes before the word in the middle of the list. If so, then you search the first half of the list the same way. Otherwise you search the second half.

Either way, you cut the remaining search space in half. If the word list has 113,809 words, it will take about 17 steps to find the word or conclude that it’s not there.

Write a function called bisect that takes a sorted list and a target value and returns the index of the value in the list, if it’s there, or None if it’s not.

Or you could read the documentation of the bisect module and use that!

**第 0041 题：**Two words are a “reverse pair” if each is the reverse of the other. Write a program that finds all the reverse pairs in the word list.

**第 0042 题：**Two words “interlock” if taking alternating letters from each forms a new word. For example, “shoe” and “cold” interlock to form “schooled.”

1. Write a program that finds all pairs of words that interlock. Hint: don’t enumerate all pairs!
2. Can you find any words that are three-way interlocked; that is, every third letter forms a word, starting from the first, second or third?

**第 0043 题：**Memoize the Ackermann function from Problem 0029 and see if memoization makes it possible to evaluate the function with bigger arguments.

**第 0044 题：**Read the documentation of the dictionary method setdefault and use it to write a more concise version of `invert_dict`. 

**第 0045 题：**If you did Problem 0038, you already have a function named `has_duplicates` that takes a list as a parameter and returns True if there is any object that appears more than once in the list.

Use a dictionary to write a faster, simpler version of `has_duplicates`.

**第 0046 题：**Two words are “rotate pairs” if you can rotate one of them and get the other (see `rotate_word` in Problem 0035).

Write a program that reads a wordlist and finds all the rotate pairs.

**第 0047 题：**Write a funciton that ties are broken by comparing words, so words with the same length appear in reverse alphabetical order. For other applications you might want to break ties at random.

Modify previous function so that words with the same length appear in random order. Hint: see the random function in the random module.

**第 0048 题：**Write a function called `most_frequent` that takes a string and prints the letters in decreasing order of frequency. 

Find text samples from several different languages and see how letter frequency varies between languages. Compare your results with the tables at http://en.wikipedia.org/wiki/Letter_frequencies . 

**第 0049 题：More anagrams!

Write a program that reads a word list from a file and prints all the sets of words that are anagrams.

Here is an example of what the output might look like:
```
    ['deltas', 'desalt', 'lasted', 'salted', 'slated', 'staled']
    ['retainers', 'ternaries']
    ['generating', 'greatening']
    ['resmelts', 'smelters', 'termless']
```
Hint: you might want to build a dictionary that maps from a set of letters to a list of words that can be spelled with those letters. The question is, how can you represent the set of letters in a way that can be used as a key?

1. Modify the previous program so that it prints the largest set of anagrams first,followed by the second largest set, and so on.
2. In Scrabble a “bingo” is when you play all seven tiles in your rack, along with a letter on the board, to form an eight-letter word. What set of 8 letters forms the most possible bingos? Hint: there are seven.

**第 0050 题：**Two words form a “metathesis pair” if you can transform one into the other by swapping two letters; for example, “converse” and “conserve.” Write a program that finds all of the metathesis pairs in the dictionary. Hint: don’t test all pairs of words, and don’t test all possible swaps. 

**第 0051 题：**Write a function named `choose_from_hist` that takes a histogram as defined and returns a random value from the histogram, chosen with probability in proportion to frequency.

A efficient algorithm is :

1. Use keys to get a list of the words in the book.
2. Build a list that contains the cumulative sum of the word frequencies. The last item in this list is the total number of words in the book, n.
3. Choose a random number from 1 to n. Use a bisection search (Problem 0040 ) to find the index where the random number would be inserted in the cumulative sum.
4. Use the index to find the corresponding word in the word list.

Write a program that uses this algorithm to choose a random word from the book. 

**第 0052 题：**Markov analysis:

1. Write a program to read a text from a file and perform Markov analysis. The result should be a dictionary that maps from prefixes to a collection of possible suffixes. The collection might be a list, tuple, or dictionary; it is up to you to make an appropriate choice. You can test your program with prefix length two, but you should write the program in a way that makes it easy to try other lengths.

2. Add a function to the previous program to generate random text based on the Markovan alysis. Here is an example from Emma with prefix length 2

```
He was very clever, be it sweetness or be angry, ashamed or only amused, at such a stroke. She had never thought of Hannah till you were never meant for me?" "I cannot make speeches, Emma:" he soon cut it all himself.
```
For this example, I left the punctuation attached to the words. The result is almost syntactically correct, but not quite. Semantically, it almost makes sense, but not quite.

**第 0053 题：**The “rank” of a word is its position in a list of words sorted by frequency: the most common word has rank 1, the second most common has rank 2, etc.

Zipf’s law describes a relationship between the ranks and frequencies of words in natural languages (http://en.wikipedia.org/wiki/Zipf's_law). Specifically, it predicts that the frequency, f, of the word with rank r is:

![](http://ww1.sinaimg.cn/large/8178ba0ejw1ep6j8kt9dwj20l601xt8h.jpg)

where s and c are parameters that depend on the language and the text. If you take the logarithm of both sides of this equation, you get:

![](http://ww2.sinaimg.cn/large/8178ba0ejw1ep6j9cj3v7j20l201ya9v.jpg)

So if you plot log f versus log r, you should get a straight line with slope -s and intercept log c.

Write a program that reads a text from a file, counts word frequencies, and prints one line for each word, in descending order of frequency, with log f and log r. Use the graphing program of your choice to plot the results and check whether they form a straight line. Can you estimate the value of s?

To make the plots, you might have to install matplotlib (see http: // matplotlib. sourceforge. net/ ).

第 0054 题：**Write a function “walks” through a directory, prints the names of all the files, and calls itself recursively on all the directories.

The os module provides a function called walk that is similar to this one but more versatile. Read the documentation and use it to print the names of the files in a given directory and its subdirectories.

**第 0055 题：**Write a function called `sed` that takes as arguments a pattern string, a replacement string, and two filenames; it should read the first file and write the contents into the second file (creating it if necessary). If the pattern string appears anywhere in the file, it should be replaced with the replacement string.

If an error occurs while opening, reading, writing or closing files, your program should catch the exception, print an error message, and exit.

**第 0056 题：**If you finish Problem 0049, you’ll see that it creates a dictionary that maps from a sorted string of letters to the list of words that can be spelled with those letters. For example, ’opst’ maps to the list [’opts’, ’post’, ’pots’, ’spot’, ’stop’, ’tops’].

Write a module that imports Solution 0049 and provides two new functions:`store_anagrams` should store the anagram dictionary in a “shelf;” `read_anagrams` should look up a word and return a list of its anagrams.

**第 0057 题：**In a large collection of MP3 files, there may be more than one copy of the same song, stored in different directories or with different file names. The goal of this exercise is to search for duplicates.

1. Write a program that searches a directory and all of its subdirectories, recursively, and returns a list of complete paths for all files with a given suffix (like .mp3). Hint: os.path provides several useful functions for manipulating file and path names.

2. To recognize duplicates, you can use `md5sum` to compute a “checksum” for each files. If two files have the same checksum, they probably have the same contents.

3. To double-check, you can use the Unix command `diff`.

**第 0058 题：**有个目录，里面是你自己写过的程序，统计一下你写过多少行代码。包括空行和注释，但是要分别列出来。 via [Yixiaohan/show-me-the-code 第 0013 题](https://github.com/Yixiaohan/show-me-the-code)

**第 0059 题：**The urllib module provides methods for manipulating URLs and downloading information from the web. The following example downloads and prints a secret message from thinkpython.com:

```python
import urllib
conn = urllib.urlopen('http://thinkpython.com/secret.html')
for line in conn:
    print line.strip()
```
Run this code and follow the instructions you see there.

**第 0060 题：**Swampy provides a module named World, which defines a user-defined type also called World. You can import it like this:

```python
from swampy.World import World
```

The following code creates a World object and calls the mainloop method, which waits for the user.

A window should appear with a title bar and an empty square. We will use this window to draw Points, Rectangles and other shapes. Add the following lines before calling mainloop and run the program again.

```
canvas = world.ca(width=500, height=500, background='white')
bbox = [[-150,-100], [150, 100]]
canvas.rectangle(bbox, outline='black', width=2, fill='green4')
```

You should see a green rectangle with a black outline. The first line creates a Canvas, which appears in the window as a white square. The Canvas object provides methods like rectangle for drawing various shapes.

bbox is a list of lists that represents the “bounding box” of the rectangle. The first pair of coordinates is the lower-left corner of the rectangle; the second pair is the upper-right corner.

You can draw a circle like this:

```python
canvas.circle([-25,0], 70, outline=None, fill='red')
```

The first parameter is the coordinate pair for the center of the circle; the second parameter is the radius.

If you add this line to the program, the result should resemble the national flag of Bangladesh (see http://en.wikipedia.org/wiki/Gallery_of_sovereign-state_flags ).

![](http://ww4.sinaimg.cn/large/8178ba0ejw1epo6fxqs76j20h60hyaar.jpg)

1. Write a function called `draw_rectangle` that takes a Canvas and a Rectangle as arguments and draws a representation of the Rectangle on the Canvas.
2. Add an attribute named color to your Rectangle objects and modify `draw_rectangle` so that it uses the color attribute as the fill color.
3. Write a function called `draw_point` that takes a Canvas and a Point as arguments and draws a representation of the Point on the Canvas.
4. Define a new class called Circle with appropriate attributes and instantiate a few Circle objects. Write a function called `draw_circle` that draws circles on the canvas.
5. Write a program that draws the national flag of the Czech Republic. Hint: you can draw a polygon like this:

```python
points = [[-150,-100], [150, 100], [150, -100]]
canvas.polygon(points, fill='blue')
```

**第 0061 题：**Write a function called `mul_time` that takes a Time object and a number and returns a new Time object that contains the product of the original Time and the number.

Then use `mul_time` to write a function that takes a Time object that represents the finishing time in a race, and a number that represents the distance, and returns a Time object that represents the average pace (time per mile).

**第 0062 题：**The datetime module provides date and time objects that are similar to the Date and Time objects in this chapter, but they provide a rich set of methods and operators.

1. Use the datetime module to write a program that gets the current date and prints the day of the week.

2. Write a program that takes a birthday as input and prints the user’s age and the number of days, hours, minutes and seconds until their next birthday.

3. For two people born on different days, there is a day when one is twice as old as the other. That’s their Double Day. Write a program that takes two birthdays and computes their Double Day.

4. For a little more challenge, write the more general version that computes the day when one person is n times older than the other.

**第 0063 题：**Download the code from this chapter (http://thinkpython.com/code/Time2.py). Change the attributes of Time to be a single integer representing seconds since midnight. Then modify the methods (and the function `int_to_time`) to work with the new implementation. You should not have to modify the test code in main. When you are done, the output should be the same as before. 

**第 0064 题：**This exercise is a cautionary tale about one of the most common, and difficult to
find, errors in Python. Write a definition for a class named Kangaroo with the following methods:

1. An `__init__` method that initializes an attribute named `pouch_contents` to an empty list.
2. A method named `put_in_pouch` that takes an object of any type and adds it to `pouch_contents`.
3. A `__str__` method that returns a string representation of the Kangaroo object and the contents of the pouch.

Test your code by creating two Kangaroo objects, assigning them to variables named kanga and roo, and then adding roo to the contents of kanga’s pouch.

Download http://thinkpython.com/code/BadKangaroo.py . It contains a solution to the previous problem with one big, nasty bug. Find and fix the bug.

**第 0065 题：**Download my code from (http://thinkpython.com/code/markov.py), and follow the steps described above to encapsulate the global variables as attributes of a new class called Markov.

**第 0066 题：**The following are the possible hands in poker, in increasing order of value (and decreasing order of probability):

pair: two cards with the same rank

two pair: two pairs of cards with the same rank

three of a kind: three cards with the same rank

straight: five cards with ranks in sequence (aces can be high or low, so Ace-2-3-4-5 is a straight and so is 10-Jack-Queen-King-Ace, but Queen-King-Ace-2-3 is not.)

flush: five cards with the same suit

full house: three cards with one rank, two cards with another

four of a kind: four cards with the same rank

straight flush: five cards in sequence (as defined above) and with the same suit

The goal of these exercises is to estimate the probability of drawing these various hands.

1. Downloadthefollowingfilesfromhttp://thinkpython.com/code:

Card.py : A complete version of the Card, Deck and Hand classes in this chapter.

PokerHand.py : An incomplete implementation of a class that represents a poker hand, and some code that tests it.

2. If you run PokerHand.py, it deals seven 7-card poker hands and checks to see if any of them contains a flush. Read this code carefully before you go on.

3. Add methods to PokerHand.py named has_pair, has_twopair, etc. that return True or False according to whether or not the hand meets the relevant criteria. Your code should work correctly for “hands” that contain any number of cards (although 5 and 7 are the most common sizes).

4. Write a method named classify that figures out the highest-value classification for a hand and sets the label attribute accordingly. For example, a 7-card hand might contain a flush and a pair; it should be labeled “flush”.

5. When you are convinced that your classification methods are working, the next step is to esti- mate the probabilities of the various hands. Write a function in PokerHand.py that shuffles a deck of cards, divides it into hands, classifies the hands, and counts the number of times various classifications appear.

6. Print a table of the classifications and their probabilities. Run your program with larger and larger numbers of hands until the output values converge to a reasonable degree of accu- racy. Compare your results to the values at http://en.wikipedia.org/wiki/Hand_rankings .

**第 0067 题：**Write an appropriately general set of functions that can draw shapes as fllow.

![](http://ww4.sinaimg.cn/large/8178ba0ejw1epoc041i4ng20b00b63zz.gif)

**第 0068 题：**The letters of the alphabet can be constructed from a moderate number of basic elements, like vertical and horizontal lines and a few curves. Design a font that can be drawn with a minimal number of basic elements and then write functions that draw letters of the alphabet.

![](http://ww1.sinaimg.cn/large/8178ba0egw1eppyc0xz65g20b00b6753.gif)

![](http://ww1.sinaimg.cn/large/8178ba0ejw1epq0ymp9oog20b00b6js3.gif)

**第 0069 题：**Read about spirals at http: // en. wikipedia. org/ wiki/ Spiral ; then write a program that draws an Archimedian spiral (or one of the other kinds).

![](http://ww4.sinaimg.cn/large/8178ba0ejw1epqitkec9og20b00b67da.gif)

**第 0070 题：**This question is based on a Puzzler that was broadcast on the radio program Car
Talk (http: // www. cartalk. com/ content/ puzzler/ transcripts/ 200725 ):

Give me a word with three consecutive double letters. I’ll give you a couple of words that almost qualify, but don’t. For example, the word committee, c-o-m-m-i-t-t-e-e. It would be great except for the ‘i’ that sneaks in there. Or Mississippi: M-i-s-s-i-s-s-i-p-p-i. If you could take out those i’s it would work. But there is a word that has three consecutive pairs of letters and to the best of my knowledge this may be the only word. Of course there are probably 500 more but I can only think of one. What is the word?

Write a program to find it.

**第 0071 题：**Here’s another Car Talk Puzzler(http://www.cartalk.com/content/puzzler/transcripts/200803):

“I was driving on the highway the other day and I happened to notice my odometer. Like most odometers, it shows six digits, in whole miles only. So, if my car had 300,000 miles, for example, I’d see 3-0-0-0-0-0.

“Now, what I saw that day was very interesting. I noticed that the last 4 digits were palindromic; that is, they read the same forward as backward. For example, 5-4-4-5 is a palindrome, so my odometer could have read 3-1-5-4-4-5.

“One mile later, the last 5 numbers were palindromic. For example, it could have read 3-6-5-4-5-6. One mile after that, the middle 4 out of 6 numbers were palindromic. And you ready for this? One mile later, all 6 were palindromic!

“The question is, what was on the odometer when I first looked?”

Write a Python program that tests all the six-digit numbers and prints any numbers that satisfy these requirements.

**第 0072 题：**Here’s another Car Talk Puzzler you can solve with a search(http://www.cartalk.com/content/puzzler/transcripts/200813):

“Recently I had a visit with my mom and we realized that the two digits that make up my age when reversed resulted in her age. For example, if she’s 73, I’m 37. We wondered how often this has happened over the years but we got sidetracked with other topics and we never came up with an answer.

“When I got home I figured out that the digits of our ages have been reversible six times so far. I also figured out that if we’re lucky it would happen again in a few years, and if we’re really lucky it would happen one more time after that. In other words, it would have happened 8 times over all. So the question is, how old am I now?”

Write a Python program that searches for solutions to this Puzzler. Hint: you might find the string method zfill useful.

**第 0073 题：**有一个单词列表，单词首字母有大写有小写。按照单词长度由小到大输出，对于长度相同的单词按字母序由小到大排序，其中小写字母要排在大写字前面。

例如, 单词列表为
```
[A, a, AB, aB]
```

则输出格式应为
```
a
A
aB
AB
```

**第 0074 题：**Here’sanotherPuzzlerfromCarTalk(http://www.cartalk.com/content/puzzler/transcripts/200717):

This was sent in by a fellow named Dan O’Leary. He came upon a common one-syllable, five-letter word recently that has the following unique property. When you remove the first letter, the remaining letters form a homophone of the original word, that is a word that sounds exactly the same. Replace the first letter, that is, put it back and remove the second letter and the result is yet another homophone of the original word. And the question is, what’s the word?

Now I’m going to give you an example that doesn’t work. Let’s look at the five-letter word, ‘wrack.’ W-R-A-C-K, you know like to ‘wrack with pain.’ If I remove the first letter, I am left with a four-letter word, ’R-A-C-K.’ As in, ‘Holy cow, did you see the rack on that buck! It must have been a nine-pointer!’ It’s a perfect homophone. If you put the ‘w’ back, and remove the ‘r,’ instead, you’re left with the word, ‘wack,’ which is a real word, it’s just not a homophone of the other two words.

But there is, however, at least one word that Dan and we know of, which will yield two homophones if you remove either of the first two letters to make two, new four-letter words. The question is, what’s the word?

To check whether two words are homophones, you can use the CMU Pronouncing Dictionary. You can download it from http://www.speech.cs.cmu.edu/cgi-bin/cmudict

You can write a function named `read_dictionary` that reads the pronouncing dictionary and returns a Python dictionary that maps from each word to a string that describes its primary pronunciation.

Write a program that lists all the words that solve the Puzzler. 

**第 0075 题：**Here’s another Car Talk Puzzler (http://www.cartalk.com/content/puzzler/transcripts/200651):

What is the longest English word, that remains a valid English word, as you remove its letters one at a time?

Now, letters can be removed from either end, or the middle, but you can’t rearrange any of the letters. Every time you drop a letter, you wind up with another English word. If you do that, you’re eventually going to wind up with one letter and that too is going to be an English word—one that’s found in the dictionary. I want to know what’s the longest word and how many letters does it have?

I’m going to give you a little modest example: Sprite. Ok? You start off with sprite, you take a letter off, one from the interior of the word, take the r away, and we’re left with the word spite, then we take the e off the end, we’re left with spit, we take the s off, we’re left with pit, it, and I.

Write a program to find all words that can be reduced in this way, and then find the longest one. This exercise is a little more challenging than most, so here are some suggestions:

1. You might want to write a function that takes a word and computes a list of all the words that can be formed by removing one letter. These are the “children” of the word.

2. Recursively, a word is reducible if any of its children are reducible. As a base case, you can consider the empty string reducible.

3. The wordlist I provided, words.txt, doesn’t contain single letter words. So you might want to add “I”, “a”, and the empty string.

4. To improve the performance of your program, you might want to memoize the words that are known to be reducible.

**第 0076 题：**For this exercise, you will write an image viewer. Here is a simple example:

```python
g = Gui()
canvas = g.ca(width=300)
photo = PhotoImage(file='danger.gif')
canvas.image([0,0], image=photo)
g.mainloop()
```

PhotoImage reads a file and returns a PhotoImage object that Tkinter can display. Canvas.image puts the image on the canvas, centered on the given coordinates. You can also put images on labels, buttons, and some other widgets:

```python
g.la(image=photo)
g.bu(image=photo)
```

PhotoImage can only handle a few image formats, like GIF and PPM, but we can use the Python Imaging Library (PIL) to read other files.

The name of the PIL module is Image, but Tkinter defines an object with the same name. To avoid the conflict, you can use import...as like this:

```python
import Image as PIL
import ImageTk
```

The first line imports Image and gives it the local name PIL. The second line imports ImageTk, which can translate a PIL image into a Tkinter PhotoImage. Here’s an example:

```python
image = PIL.open('allen.png')
photo2 = ImageTk.PhotoImage(image)
g.la(image=photo2)
```

1. Download image_demo.py, danger.gif and allen.png from http://thinkpython.com/code. Run image_demo.py. You might have to install PIL and ImageTk. They are probably in your software repository, but if not you can get them from pythonware.com/products/pil/ .

2. In image_demo.py change the name of the second PhotoImage from photo2 to photo and run the program again. You should see the second PhotoImage but not the first.

The problem is that when you reassign photo it overwrites the reference to the first PhotoIm- age, which then disappears. The same thing happens if you assign a PhotoImage to a local variable; it disappears when the function ends.

To avoid this problem, you have to store a reference to each PhotoImage you want to keep. You can use a global variable, or store PhotoImages in a data structure or as an attribute of an object.

3. Starting with this example, write a program that takes the name of a directory and loops through all the files, displaying any files that PIL recognizes as images. You can use a try statement to catch the files PIL doesn’t recognize.

When the user clicks on the image, the program should display the next one.

4. PIL provides a variety of methods for manipulating images. You can read about them at http://pythonware.com/library/pil/handbook . As a challenge, choose a few of these methods and provide a GUI for applying them to images.

**第 0077 题：**有1000瓶啤酒，每喝完一瓶得到一个空瓶子，每3个空瓶子又能换1瓶啤酒，喝掉以后又得到一个空瓶子。问总共能喝多少瓶啤酒?还剩多少空瓶子

**第 0078 题：**对文件的批量操作

1. 将 aaaBbbCcc 的文件名转化为 aaa-bbb-ccc
2. 在文件中添加相关的字段
