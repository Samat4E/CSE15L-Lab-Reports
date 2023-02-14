# Lab Report 2 - Servers and Bugs (Week 3)
First we have to write a web server called StringServer that supports the path and behavior given below. It should keep track of a   
single string that gets added to by incoming requests. So by the help of the givin NumberServer web server I come to code the String server  
as showen below. 
![image](https://user-images.githubusercontent.com/122564368/218645233-5075dc81-bf5b-432f-a5a2-da9f21290d64.png)
 And when we run the code a new web window will pop out and we can add the given string over the url of the web  
 and here are the examples  
 
 ![image](https://user-images.githubusercontent.com/122564368/218663456-88fb356a-b31a-477f-b32a-f33b92371f21.png)
 ![Screenshot 2023-02-13 225935](https://user-images.githubusercontent.com/122564368/218663505-5ffecd50-a53f-4dfc-8697-c1d743381ba7.png)  
 
## Symptoms and Failure-inducing Inputs

## Setup
  In labs 2 and 3, we'll demonstrate how to identify bugs and analyze the symptoms from an array list step-by-step.  
  We begin by forking the repository to our github desktop from a supplied github URL, https://github.com/ucsd-cse15l-w23/lab3.   
  then we clone it to our github and open it through VScode.

![image](https://user-images.githubusercontent.com/122564368/215680175-3eab9d04-446e-4b02-b2a0-41351106c5ae.png)
   
 **There are a few relevant files Like in the folder**  
 ***-->ArrayExamples.java  
-->ArrayTests.java  
-->ListExamples.java  
-->LinkedListExample.java  
-->FileExample.java***  
## Here after running the following Junit commands we Successfully created the output
$ javac -cp lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar:. MarkdownParseTest.java  
$ java -cp lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar:. org.junit.runner.JUnitCore MarkdownParseTest  

![image](https://user-images.githubusercontent.com/122564368/215682540-1322af3b-7722-4071-84d4-3db01f2e1fb1.png)

 After downloading it and opening the specified folder in VScode, we attempt to run the file ArrayExample.java and   
 it runs without any bags detected so we need to write more tests to find the bags. on the ArrayTests.java 
 function provides some tests. It executes tests using assertEquals function using JUnit framework.    
 
 **Junit** is a unit testing open-source framework for the Java programming language. Java Developers use this  
 framework to write and execute automated tests.  
 

![image](https://user-images.githubusercontent.com/122564368/215683252-2e3a9772-ccb2-43a4-b89e-07382bd92a45.png)

![image](https://user-images.githubusercontent.com/122564368/215680008-7e956235-80da-4eac-a02c-cffc6c69c73b.png)  

--> Here we have two failers so we have to find the bags and try to make somechanges in our main method ArrayExample.java  

![image](https://user-images.githubusercontent.com/122564368/218657817-22966937-2e14-4c63-8683-70947d3a5a47.png)

## After making the changes we run the test again and here is the result our test passed 

![image](https://user-images.githubusercontent.com/122564368/218658273-dbac53c3-7a32-43c8-884a-5afe4d30a13f.png)    

## Finally 
    From lab in week 2 and 3 I learned maney usefull things. the first thing that i lerned is what a web servers   
    can do.Here i learned that a programs that take a URL as input and respond with the text of a web page this  
    was my first time doing this thing again in lab 3 i learned about finding Symptoms and bags this wasnt new to   
    me but learned some skills too. 





