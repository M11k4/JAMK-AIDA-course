# 1) Harjoituksia kontrollirakenteista

## 1-1) Byte, Kilobyte, Megabyte, Gigabyte converter

Make a program that calculates the kB/MB/GB based on the input bytes.

Insert bytes and then your program calculates bytes in a kilobyte, megabyte and gigabyte.
For counting you must use real mega, giga and tera definitions (so for example 2^20 or 2^30).
Background information http://www.whatsabyte.com/

An Example of Program Execution:

	Give your input in bytes>5206000
	bytes 		 5206000 B
	Kilobytes	 5083.984375 KB
	Megabytes	 4.9648284912109375 MB
	Gigabytes	 0.004848465323448181 GB


## 1-2) Grade calculator

Make a program that calculates the grade based on the input data

Ask the user for two points:
* exam points   (0-24) and
  * demo points  (0-12)
  and calculate the total grade between 0-5 based on the following table:


      >  = 32 	=> 5
      >  = 28 	=> 4
      >  = 24 	=> 3
      >  = 20 	=> 2
      >  = 15 	=> 1
      < 15   	=> 0


An Example of Program Execution:

	How many exam points did you get (0-24)?19
	How many demo points did you get (0-12)?8
	With total points 27, the final grade was 3

## 1-3) Read input args and calculate sum

Make a program that read command line input (integer) arguments and calculate sum based on arguments

* Give only integers as a command line arguments
* calculate the end results based on the integers
* Use `for` loop for calculating the results

An Example of Program Execution:

	python model_01_04_int_args_sum.py 4 5 6 7 12 15
	Total sum for args $['4', '5', '6', '7', '12', '15'] is '49'


## 1-4) Multiplication table

Calculate the multiplication table
based on the upper limit number entered by the user

An Example of Program Execution:

	upper limit>4
	1 * 1 = 1
	1 * 2 = 2
	1 * 3 = 3
	1 * 4 = 4
	2 * 1 = 2
	2 * 2 = 4
	2 * 3 = 6


## 1-5) calculate a/e characters in a string

Give a string and search how many 'a/A' or 'e/E' letters there are in the string

An Example of Program Execution:

	Give a string>Jumping Errors and some test arrays Added
	a/A letters:  4
	e/E letters:  4

## 1-6) calculate all characters in a string

* How to find out all small letters in a given string?
* And then count the number of lower letters in that string?

An Example of Program Execution:

	Give a string>First test string or character SET input
	' ': 6
	'a': 2
	'c': 2
	'e': 3
	'f': 1
	'g': 1
	'h': 1
	'i': 3
	'n': 2
	'o': 1
	'p': 1
	'r': 5
	's': 4
	't': 7
	'u': 1
