# Docker

<h3>Usage : This document describes how to consume the rest services created for Docker Project </h3>

<h4>APPLICATION END POINT</h4>

<h4> Table Application</h4>
<h6> This app have the interface to accept number input and returns a table of that particular number </h6>

<h4>http://localhost:8080/program.php?x=4 </h4>

Sample Result:



<br>

<h3>API END POINT</h3>

<h4> Prime Number Validator </h4>

<h6> This service validates the given number is a prime or not using get request. Returns a json formatted result with a message whether the input is prime or not. Sample URL is given below </h6>

<h4>http://localhost:8080/RestApp/index.php/api/is_prime/id/1</h4>

Sample Result:

{"input":1,"result":"Neither prime nor composite"}
