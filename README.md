# Docker

<h3>Usage : This document describes how to consume the rest services created for Docker Project </h3>

<h4>APPLICATION END POINT</h4>

<h4> Table Application</h4>
<h6> This app have the interface to accept number input and returns a table of that particular number </h6>

<h4>http://localhost:8080/program.php?x=2 </h4>

Sample Result:

{"input":"2","result":"2 * 1 = 2
2 * 2 = 4
2 * 3 = 6
2 * 4 = 8
2 * 5 = 10
2 * 6 = 12
2 * 7 = 14
2 * 8 = 16
2 * 9 = 18
2 * 10 = 20
"}



<br>

<h3>API END POINT</h3>

<h4> Palindrome or not </h4>

<h6> A palindrome is a number that can be read from right to left, and yet still remains the same as the number read left to right. For example, ‘121’ and ‘959’ are both palindromes because if you read the numbers from right to left they are equivalent to the numbers read left to right. Below is the example for palindrome and all the examples realted to palindrome are in JSON format </h6>

<h4> http://localhost:8080/program1.php?x=121 </h4>

Sample Result:

{"input":"121","result":"Palindrome"}
