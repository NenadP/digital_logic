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

 ## 1.8
 Convert the decimal number 431 to binary in two ways: (a) convert directly to binary;
(b) convert first to hexadecimal and then from hexadecimal to binary. Which method is faster?

(a)
$$
431 \div 2 = 215 r 1 \\
215 \div 2 = 107 r 1 \\
107 \div 2 = 53  r 1 \\
53  \div 2 = 26  r 1 \\
26  \div 2 = 13  r 0 \\
13  \div 2 = 6   r 1 \\
6   \div 2 = 3   r 0 \\
3   \div 2 = 1   r 1 \\
1   \div 2 = 0   r 1 \\
\\[1em]
Result = (1\ 1100\ 0011)_{2} \\
$$

(b)
$$
431 \div 16 = 26 r 15 = F \\
26  \div 16 = 1  r 10 = A \\
1   \div 16 = 0  r 1  = 1 \\

Hex = (1AF)_{16} \\
\\[2em]
\text {Hex to binary:} \\
\\[1em]
Fh = 1111b \\
Ah = 1010b \\
1h = 0001b \\
\\[1em]
Result = (0001\ 1100\ 0011)_{2} = \\
(1\ 1100\ 0011)_{2}
$$

(a) is more straightforward, (b) has possibly less steps

## 1.9
Express the following numbers in decimal:

$$
(a)*\ (10110.0101)_{2} \\
(b)*\ (16.5)_{16} \\
(c)*\ (26.24)_{8} \\
(d)\ (DADA.B)_{16} \\
(e)\ (1010.1101)_{2} \\
$$

(a)

$$
1 \times 2^{-4} = 0.0625 \\
0 \times 2^{-3} = 0 \\
1 \times 2^{-2} = 0.25 \\
0 \times 2^{-1} = 0 \\
0 \times 2^0 = 0 \\
1 \times 2^1 = 2 \\ 
1 \times 2^2 = 4 \\
0 \times 2^3 = 0 \\
1 \times 2^4 = 16 \\
\\[1em]
note: 1 \times 2^{-4} = {1 \over 2^{4}} = {1 \over 16} = 0.0625   \\
\\[1em]
Result = 16 + 4 + 2 + 0.25 + 0.0625 = \\
(22.3125)_{10}
$$

(b)
$$
5 \times 16^{-1} = 0.5 \\
6 \times 16^0 = 6 \\
1 \times 16^1 = 16 \\ 
\\[1em]
note: 5 \times 16^{-1} = {5 \over 16^{1}} = {5 \over 16} = 0.3125 \\
\\[1em]
Result = 24 + 0.3125 = \\
(24.3125)_{10}
$$

(c)*
$$
(26.24)_{8} 
4 \times 8^{-2} = 0.0625 \\
2 \times 8^{-1} = 0.250 \\
6 \times 8^0 = 6 \\
2 \times 8^1 = 16 \\
Result = 24 + 0.3125 = \\
(24.3125)_{10}
$$

(d)
$$
B \times 16^{-1} = 0.6875 \\
A \times 16^0 = 10 \\
D \times 16^1 = 208 \\ 
A \times 16^2 = 2560 \\ 
D \times 16^3 = 53248 \\ 
Result = 10 + 208 + 2560 + 53248 + 0.6875 = \\
(56026.6875)_{10}
$$

(e)
$$
1 \times 2^{-4} = 0.0625 \\
0 \times 2^{-3} = 0 \\
1 \times 2^{-2} = 0.25 \\
1 \times 2^{-1} = 0.5 \\
0 \times 2^0 = 0 \\
1 \times 2^1 = 2 \\ 
0 \times 2^2 = 0 \\
1 \times 2^3 = 8 \\
Result = 8 + 2 + 0.5 + 0.25 + 0.0625 = \\
(10.8125)_{10}
$$

## 1.10
Convert the following binary numbers to hexadecimal and to decimal: (a) 1.10010,
(b) 110.010. Explain why the decimal answer in (b) is 4 times that in (a).

(a)
$$
0 \times 2^{-5} = 0 \\
1 \times 2^{-4} = 0.0625 \\
0 \times 2^{-3} = 0 \\
0 \times 2^{-2} = 0 \\
1 \times 2^{-1} = 0.5 \\
1 \times 2^0 = 1 \\
Result = 1 + 0.5 + 0.0625 = \\
(1.5625)_{10} \\
\\[1em]
to Hex:
\\[0.5em]
0.5625 \times 16 = 9 \\
\text {fraction part} =  0.9 \\
Result = (1.9)_{16}
$$

(b)
$$
0 \times 2^{-3} = 0 \\
1 \times 2^{-2} = 0.25 \\
0 \times 2^{-1} = 0 \\
0 \times 2^0 = 0 \\
1 \times 2^1 = 2 \\
1 \times 2^2 = 4 \\
Result = 6.25 = \\
(6.25)_{10} \\
\\[1em]
to Hex:
\\[0.5em]
0.25 \times 16 = 4 \\
\text {fraction part} =  0.4 \\
Result = 6 + 0.4 = (6.4)_{16} \\
$$


Since we shifted bits to the left 2 places, its
equal to multiplying number by 

$$
2^2 = 4 \\
$$
Showing intermediary step of multiplication as well:  
original, x2, x4
$$
1.10010 \\
11.0010 \\
110.010 \\
$$

## 1.11
Perform the following division in binary: 111011 ÷ 101.

$$
TODO
$$