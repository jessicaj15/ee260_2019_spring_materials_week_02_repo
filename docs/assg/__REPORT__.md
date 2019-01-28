---
title: Homework1
author: Jessica Jones
partner: Alexa Fernando, Christine Ramos
date: 1/28/2019
---

In the report, complete the following.
- Explain the objective of the problem.
- Give your solution.
- Include all your project codes in the [codes/assg](../../codes/assg) folder,
  if required.
- Explain your code snippets, if required.
- Include screenshots of the simulations in this folder, and insert them into
  the markdown file, if required.
- Explain why the simulations are correct, if required.

You can embed math equations into Github Markdown file using a [web service](https://www.codecogs.com/latex/eqneditor.php)

## (5 pts)
What is a digital signal and how does it differ from an analog signal? Give two
everyday examples of digital phenomena (e.g., a window can be open or closed) and
two everyday examples of analog phenomena. 

The objective of this problem is to understand analog and digital signals enough to give examples of each and to differentiate between them. 

A digital signal is a signal with a finite amount of values, whereas an analog signal is a signal with an infinite amount of values. For example, a digital phenomenon could be a light turning on or off or if a password is accepted (it is either right or wrong).  
Examples of analog phenomena could include the amount of liquid in a cup or the loudness of a sound someone produces by singing. 

## (5 pts)
Assume that a signal is encoded using 12 bits. Assume that many of the encodings
turn out to be either 000000000000, 000000000001, or 111111111111. We
thus decide to create compressed encodings by representing 000000000000 as
00, 000000000001 as 01, and 111111111111 as 10. 11 means that an
uncompressed encoding follows. Using this encoding scheme, decompress the following encoded stream:

00 00 01 10 11 010101010101 00 00 10 10

The objective of this problem is to demonstrate your knowledge of compression. 
In order to decompress the above encoded stream, we can use the code above (for example, replacing ‘00’ with ‘000000000000’). The string “00 00 01 10 11 010101010101 00 00 10 10” would be decompressed to “000000000000 000000000000 000000000001 111111111111 010101010101 000000000000 000000000000 111111111111 111111111111” 

## (5 pts) Wakerly, Problem 2.2 (a)-(c)
Convert the following octal numbers into binary and hexadecimal:
- a. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;${4321}_{8}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;${4321}_{8}" title="${4321}_{8}" /></a>
- b. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{1772631}_{8}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{1772631}_{8}" title="{1772631}_{8}" /></a>
- c. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{533434}_{8}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{533434}_{8}" title="{533434}_{8}" /></a>

The objective of this problem is to demonstrate that you understand the relation between octal, binary, and hexadecimal enough to convert numbers. 

![HW1]( https://raw.githubusercontent.com/jessicaj15/ee260_2019_spring_materials_week_02_repo/master/docs/assg/HW1.jpg)

## (5 pts) Wakerly, Problem 2.5 (a)-(f)
Convert the following numbers into decimal:
- a. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{1011101}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{1011101}_{2}" title="{1011101}_{2}" /></a>
- b. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{173016}_{8}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{173016}_{8}" title="{173016}_{8}" /></a>
- c. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{10110001}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{10110001}_{2}" title="{10110001}_{2}" /></a>
- d. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{66.27}_{8}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{66.27}_{8}" title="{66.27}_{8}" /></a>
- e. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{10101.1001}_{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{10101.1001}_{2}" title="{10101.1001}_{2}" /></a>
- f. <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;{FCB6}_{16}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;{FCB6}_{16}" title="{FCB6}_{16}" /></a>

The objective of this problem is to demonstrate your ability to convert numbers from binary, octal, and hexadecimal into decimal.  

![HW2]( https://raw.githubusercontent.com/jessicaj15/ee260_2019_spring_materials_week_02_repo/master/docs/assg/HW2.jpg)

## (5 pts) Wakerly, Problem 2.7 (a)-(b)
Add the following pairs of binary numbers, showing all carries:
- a.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\begin{matrix}&space;&&space;110011&space;\\&space;&plus;&space;&&space;011001&space;\\&space;&&space;---&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\begin{matrix}&space;&&space;110011&space;\\&space;&plus;&space;&&space;011001&space;\\&space;&&space;---&space;\end{matrix}" title="\begin{matrix} & 110011 \\ + & 011001 \\ & --- \end{matrix}" /></a>
- b.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\begin{matrix}&space;&&space;101110&space;\\&space;&plus;&space;&&space;100101&space;\\&space;&&space;---&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\begin{matrix}&space;&&space;101110&space;\\&space;&plus;&space;&&space;100101&space;\\&space;&&space;---&space;\end{matrix}" title="\begin{matrix} & 101110 \\ + & 100101 \\ & --- \end{matrix}" /></a>

The objective of this problem is to demonstrate the knowledge of adding binary numbers, especially understanding the idea of a base of 2 for handling carries. 

![HW3]( https://raw.githubusercontent.com/jessicaj15/ee260_2019_spring_materials_week_02_repo/master/docs/assg/HW3.jpg)

## (5 pts) Wakerly, Problem 2.9 (a)-(b)
Add the following pairs of octal numbers:
- a.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\begin{matrix}&space;&&space;1362&space;\\&space;&plus;&space;&&space;4231&space;\\&space;&&space;---&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\begin{matrix}&space;&&space;1362&space;\\&space;&plus;&space;&&space;4231&space;\\&space;&&space;---&space;\end{matrix}" title="\begin{matrix} & 1362 \\ + & 4231 \\ & --- \end{matrix}" /></a>
- b.  
<a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\begin{matrix}&space;&&space;47135&space;\\&space;&plus;&space;&&space;05145&space;\\&space;&&space;---&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\begin{matrix}&space;&&space;47135&space;\\&space;&plus;&space;&&space;05145&space;\\&space;&&space;---&space;\end{matrix}" title="\begin{matrix} & 47135 \\ + & 05145 \\ & --- \end{matrix}" /></a>

The objective of this problem is to demonstrate the knowledge of adding octal numbers, specifically understanding the concept of a base of 8 to handle carries. 

![HW4]( https://raw.githubusercontent.com/jessicaj15/ee260_2019_spring_materials_week_02_repo/master/docs/assg/HW4.jpg)

## (5 pts)
Convert the following decimal numbers to binary numbers using the divide-by-2
method:
- a. 19
- b. 30

The objective of this problem is to demonstrate your ability to apply the divide-by-2 method to convert decimal numbers to binary numbers. 

![HW5]( https://raw.githubusercontent.com/jessicaj15/ee260_2019_spring_materials_week_02_repo/master/docs/assg/HW5.jpg)

## (5 pts)
Convert the decimal number 128 to the following number systems:
- a. binary
- b. hexadecimal
- c. base three
- d. base five
- e. base fifteen

The objective of this problem is to show your ability to convert from decimal to another base: binary, hexadecimal, three, five, and fifteen. 

![HW6]( https://raw.githubusercontent.com/jessicaj15/ee260_2019_spring_materials_week_02_repo/master/docs/assg/HW6.jpg)
