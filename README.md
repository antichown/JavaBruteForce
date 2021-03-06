# Java Brute Force
## BruteForce Characters Generator

### Usage:
1. clone project using: **git clone https://github.com/HussamHeriz/JavaBruteForce.git**
2. ```cd JavaBruteForce```
3. Compile Java File using: ```javac BruteForce.java```
4. ```java BruteForce {length} {characters seperated by comma ,} {output_file}```

### Notes
#### **Length:** is the length of string that is generated by possibilities
#### **characters:** List of characters eg: 0,1,2,3
#### **output_file** Destination file to save results to, you can specify the extension or not

### Screenshots
![abc_2_digits](https://github.com/HussamHeriz/JavaBruteForce/blob/master/screenshots/1.jpg?raw=true)
![8_digits_0-9](https://github.com/HussamHeriz/JavaBruteForce/blob/master/screenshots/2.jpg?raw=true)


### Help
While program is running you can any time press enter to show completion in percentage
Or you can write exit then enter to exit the execution

### Time Elapsed
#### Using AWS Cloud Computing (EC2 a2.micro) Server

4 digits of chars 0-9 : 0.01 seconds<br>
5 digits of chars 0-9 : 0.1 seconds<br>
6 digits of chars 0-9:  1.2 seconds<br>
7 digits of chars 0-9:  13.2 seconds<br>
8 digits of chars 0-9:  96.3 seconds<br>

### Example
```
java BruteForce 2 0,1,2,3,4,5,6,7,8,9 output.txt
```
output.txt is generated with following content:

```
00
01
02
03
04
05
06
07
08
09
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
83
84
85
86
87
88
89
90
91
92
93
94
95
96
97
98
99
```
