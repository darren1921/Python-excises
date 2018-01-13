# Python-excises
simple Python excises
题目1：有四个数字：1、2、3、4，能组成多少个互不相同无重复数字的三位数？各是多少？

Thinking:三位数，每个数字都可能是1—4的任意一个，把所有情况全部列出来，去掉三个数字相等的情况。

#程序
for i in range(1,5):
    for j in range(1,5):
        for k in range(1,5):
            if(i!=k)and(i!=j)and(j!=k):
                print(100*i+10*j+k) 
