# Chapter 1: Digital Systems and Binary Numbers

## 1.1 
List the octal and hexadecimal numbers from 16 to 32. Using A and B for the last two
digits, list the numbers from 8 to 28 in base 12.


**Octal:**

First number:  
$$
16 \div 8 = 2, \ r = 0 \\
2 \div 8 = 0, \ r = 2 \\
16_{10} = 20_{8} \\
$$

Result: 
$$
(20, 21, 22, 23, 24, 25, 26, 27, 30, 31, 32, 33, 34, 35, 36, 37, 40)_{8}
$$

**Hex:**

First number:
$$
16 \div 16 = 1,\ r = 0 \\
1 \div 16 = 0, \ r = 1 \\
16_{10} = 10_{16} \\
$$

Result:
$$
(10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 1A, 1B, 1C, 1D, 1E, 1F, 20)_{16}
$$

**Base 12:**

First number:
$$
8 \div 12 = 0, \ r = 8 \\
8_{10} = 8_{12} \\
$$

Result:
$$
(8, 9, A, B, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 1A, 1B, 20, 21, 22, 23, 24)_{12}
$$

## 1.2* 
What is the exact number of bytes in a system that contains (a) 32K bytes, (b) 64M bytes, and (c) 6.4G bytes?

**(a)**
$$
32K = 32 \times 1024 = 32768
$$

**(b)**
$$
64M = 64 \times 1024^2 = 67108864
$$

**(c)**
$$
6.4G = 6.4 \times 1024^3 = 6.4 \times 1073741824 = 6871947673.6 \approx 6871947674 \text{ bytes}
$$

## 1.3 
Convert the following numbers with the indicated bases to decimal:

**(a)* 4310 base 5**

$$
4310 \div 5 = 862, r = 0 \\
862 \div 5 = 172, r = 2 \\
172 \div 5 = 34, r = 2 \\
34 \div 5 = 6, r = 4 \\
6 \div 5 = 1, r = 1 \\
1 \div 5 = 0, r = 1 \\
\\[1em]
Result = (114220)_{5}
$$

**(b)* 198 base 12**

$$
198 \div 12 = 16, r = 6 \\
16 \div 12 = 1, r = 4 \\
1 \div 12 = 0, r = 1 \\
\\[1em]
Result = (146)_{12}
$$

**(c) 435 base 8**

$$
435 \div 8 = 54, r = 3 \\
54 \div 8 = 6, r = 6 \\
6 \div 8 = 0, r = 6 \\
\\[1em]
Result = (663)_{8}
$$

**(d) 345 base 6**

$$
345 \div 6 = 57, r = 3 \\
57 \div 6 = 9, r = 3 \\
9 \div 6 = 1, r = 3 \\
1 \div 6 = 0, r = 1 \\
\\[1em]
Result = (1333)_{6}
$$

## 1.4
What is the largest binary number that can be expressed with 16 bits? What are the 
equivalent decimal and hexadecimal numbers?

$$
1111\ 1111\ 1111\ 1111b \\
2^{16} = 65,535d \\
FFFFh \\
$$

## 1.5* 
Determine the base of the numbers in each case for the following operations to be correct:

**(a) 14/2 = 5**

$$
{(14)_{b} \over (2)_{b}} = (5)_{b} \\
\\[1em]
{b + 4 \over 2} = 5 \\
\\[1em]
b + 4 = 10 \\
\\[1em]
b = 10 - 4  = 6 \\
\\[1em]
b = 6
$$

**(b) 54/4 = 13**

$$
{(54)_{b} \over (4)_{b}} = (13)_{b} \\
\\[1em]
{5b + 4 \over 4} = b + 3 \\
\\[1em]
5b + 4 = (b + 3) \times 4
\\[1em]
5b + 4 = (b  \times 4) +  (3 \times 4) \\
\\[1em]
5b + 4 = b4 + 12 \\
\\[1em]
5b - 4b + 4 = 12
\\[1em]
b + 4 = 12
\\[1em]
b = 12 - 4
\\[1em]
b = 8
$$

**(c) 24 + 17 = 40**

$$
2b + 4 + b + 7 = 4b
\\[1em]
3b + 4 + 7 = 4b
\\[1em]
11 = 4b - 3b
\\[1em]
b = 11
$$


## 1.6*
 The solutions to the quadratic equation x^2 - 11x + 22 = 0 are x = 3 and x = 6. What is the base of the numbers?

 $$
 3 \times 3 - 11 \times 3 + 22 = 0 \\
 9 - (b + 1 \times 3) + 22 = 0 \\
 9 - 3b - 3 + 2b + 2 = 0 \\
 - 3b + 2b + 9 - 3 + 2 = 0 \\
 -b + 6 + 2 = 0  \\
 -b + 8 = 0  \\
 b = 8  \\
 $$

 
 $$
 6 \times 6 - 11 \times 6 + 22 = 0 \\
 36 - (b + 1 \times 6) + 22 = 0 \\
 36 - 6b - 6 + 2b + 2 = 0 \\
 -4b + 36 -6 + 2 = 0 \\
 -4b  + 36 - 4 = 0 \\
 -4b + 32 = 0  \\
 4b = 32  \\
 4b \div 4 = 32 \div 4 \\
 b = 8
 $$


 ## 1.7*
 Convert the hexadecimal number 64CD to binary, and then convert it from binary to octal.

$$
 (64CD)_{16} = \\
 \text {convert each place to binary counterpart}  \\
 (0110\ 0100\ 1100\ 1101)_{2} = \\
 \text {shift spaces to 3 places }  \\
 (0\ 110\ 010\ 011\ 001\ 101)_{2} = \\ 
 (62315)_{8}
 $$