# Lab Report 3 
##  ---> Researching Commands
**Lab 3** is about research commands and our teacher gave as to chose from these three commands those are *less, find, and grep*. and i choose  
grep command   
and with the help of grep --help command i found many interesting command-line options. and here i am going to show you 2   
examples using 4 grep commands.  

![image](https://user-images.githubusercontent.com/122564368/221735161-7809c009-8f70-403a-9eb9-d7371eecc8b2.png)  

## grep -w 
The **-w** help us to Check for the whole words in a file by default, grep matches the given string/pattern even if it is found as a substring  
in a file. The -w option to grep makes it match only the whole words.  
let's see two examples using the grep -w command  

Here -w flag is used to output all those lines in .txt containing **day** as a whole word and not as a sub-string.
![image](https://user-images.githubusercontent.com/122564368/221748538-f610b731-18f3-42f2-bbf4-1d2a4d38aecb.png)  

 ***Lets have second example in different file.txt***  
 Here -w flag is used to output all those lines in Kauffman.txt containing **they** as a whole word and not as a sub-string.  
 ![image](https://user-images.githubusercontent.com/122564368/221750090-b9781f89-0391-4be8-8f58-e9f7f9374445.png)  
 ---> So from this two examples we learned that **-w** is used to check the given word in whole words not in sub string.
 
 ## grep -o
 The **grep -o** used to display only the matched pattern. this grep displays the entire line which has the matched string only.    
 unlike the grep -w the grep -o flag displays only the matched pattern instead of displaying the entire string or line which contains it.  
 let's see what is the exact difference with the grep - w command using the same examples and the same file.txt.  
 
 ------> Here -o flag is used to output all those lines in Kauffman.txt containing **they**.  
 
 ![image](https://user-images.githubusercontent.com/122564368/221752197-4d5d27ee-13fc-4261-8d97-279fbbbd405a.png)  
 
  And the Second example from the .txt file is
     ------> Here -o flag is used to output all those lines in Abernathy.txt containing **day**.
  
  ![image](https://user-images.githubusercontent.com/122564368/221752591-2b9cc39c-183c-42bc-ba3b-19c05afe0364.png)
  
  *From this two example we learned the different uses of grep -W and grep-o commands

  

 




