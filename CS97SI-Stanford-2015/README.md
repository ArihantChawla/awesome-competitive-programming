(Stanford CS971SI: Introduction to Programming Contests)[http://web.stanford.edu/class/cs97si/]
Curated for PEC by (Arihant Chawla)[https://github.com/arihantchawla]
***

# Lecture Slides
***

## Lecture 1
***

### Topics
1. Introduction
2. Mathematics
3. Data structures
4. Dynamic programming (DP)
5. Combinatorial games
6. Graph algorithms
7. Shortest distance problems
8. Network flow
9. Geometric algorithms
10. String algorithms
***

### ProgrammingContests
+ PEC ACM Local Programming Contest
+ ACM-ICPC
	- Asia Regional
	- World Finals
+ Online Contests
	- TopCoder, Codeforces
	- Google Code Jam
+ And many more...
***

### How to Practice
+ Online Judges
+ Weekly Practice Contests

#### Online Judges
+Websites with Automated Judges
	-Real contest problems
	-Immediate feedback
+A few good OJs:
	-CodeForces
	-TopCoder
	-Perking OJ
	-Sphere OJ
	-UVa OJ
***

#### Weekly Practice Contests
+Every Sunday 11am-4pm online
+Open to anyone interested
+Real contest problems from many sources
+Get added to the (PEC ACM Slack Channel)[pecacm.slack.com]
***
***

###Example 
1. Read the problem statement
	- Check the input/output specification!
2. Make the problem abstract
3. Design an algorithm 
	- Often the hardest step
4. Implement and debug
5. Submit
6. AC: Accepted/Correct
	- if not, go back to 4
*** 

####Problem Solving Example
+ POJ 1000: A+B Problem
	- Input: Two space-separated integers a,b
	- Constraints: 0 =< a,b =< 10
	- Output: a+b

####POJ 1000 Code

```c
	#include<stdio.h>
	int main()
	{
		int a,b;
		scanf("%d%d", &a, &b);
		printf("%d\n", a+ b);
		return 0;
	}
```
***

####Another Example
+POJ 10004: Financial Management
	- Input: 12 floating point numbers on separate lines
	- Output: Average of the given numbers
+ Just a few more bytes than POJ 1000...


####POJ 1004 Code in C/C++

```cpp
	#include<iostream>
	using namespace std;
	
	int main(){
		double buf, sum =0;
		for(int iter=0; iter<12; iter++) {
			cin >> buf; //scanf("%lf", &buf);
			sum += buf;
		}
		double avg = sum/12;
		cout << avg << endl; // c-> printf("$%.21f\n, sum /12.0);
		return 0;
	} 
```
***

###Something to think about 
+ What if the given numbers are HUGE?
+ Not all the input constrainrs are explicit
	- Hidden constrainrs are generally "reasonable"
+ Always think about the worst case scenario, edge cases, etc.
***

###Grading Policy
+You can either:
	- Solve a given number of POJ problems on the course webpage
	- OR, participate in 5 or more weekly practice contests
+ If you have little experience, solving POJ problems is recommended
	= Of course doing both of them is better
***

### PEC ACM Team Notebook

+ Link 
+ Implementation of many algorithms we'll learn
+ Policy on notebook usage:
	- Don't copy paste anything from the notebook!
	- At least type everything yourself
	- Let me know of any error or suggestion

### Links
+ (Course website)[http://cs97si.stanford.edu]
+ (Stanford ACM Team Notebook)[http://stanford.edu/ ~liszt90/acm/notebook.html]
+ (Peking Online Judge) [http://poj.org]
+ (USACO Training Gate) [http://ace.delos.com/usacogate]
+ (Online discussion board) [http://piazza.com/class#winter2012/cs97si/]


