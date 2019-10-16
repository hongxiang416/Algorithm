算法设计与分析：统计数字问题

题目描述

    问题描述：
         一本书的页码从自然数 1 开始顺序编码直到自然数 n。书的页码按照通常的习惯编排，每个页码都不含多余的前导数字 0。例如，第 6 页用数字 6 表示，而不是 06 或 006 等。数字计数问题要求对给定书的总页码 n，计算出书的全部页码中分别用到多少次数字 0，1，2，…，9。 

    编程任务：
        给定表示书的总页码的 10 进制整数 n (1≤n≤109) 。编程计算书的全部页码中分别用到多少次数字 0，1，2，…，9。 
        
输入
    给出表示书的总页码的整数 n

输出
    输出共有10行，在第 k 行输出页码中用到数字 k-1 的次数，k=1，2，…，10。 

样例输入
    11
    
样例输出
    1
    4
    1
    1
    1
    1
    1
    1
    1
    1
    
提示
    输入范围1-1000000000