# CCPonCodeForces

Learn CPP from problem A.   
one problem a day   
maybe

## 949A - Zebras

### code
[949AZebras.cpp](949AZebras.cpp)

## 949B - A Leapfrog in the Array
### code
[949BALeapfrogintheArray.cpp](949BALeapfrogintheArray.cpp)

## The 16th UESTC Programming Contest Preliminary - E - Charlie
### 题目
[E - Charlie]()
### 题解
本题大约是CF上div2的A题水平；
容易发现，所有在1前面的0都将被删掉；    
使用两个计数器：zerocount记录零的个数；onecount记录不可能被删除的1(即在0前面的1)；   
按顺序读取数列，当读取到0时，zerocount加一；读取到1时，判断前面是否有0（zerocount是否等于零），有就zerocount减一；否则onecount加一；   
答案为两个计数器之和。   
### code
[CDOJ_E.cpp](CDOJ_E.cpp)
## The 16th UESTC Programming Contest Preliminary - G - Find Substring
### 题目
[G - Find Substring]()
### 题解
注意到子数列定长时该题就迎刃而解；
以母序列开头为开头计算子序列的各个字母个数与所求子数列的数组比较；
如果不匹配则向右移动，加上右边一个字母的个数，减去左边一个字母的个数,再次比对；
可以有效减少求字母个数的算法复杂度。
### code
[CDOJ_G.cpp](CDOJ_G.cpp)