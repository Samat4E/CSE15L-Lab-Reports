# Lab Report 3 
##            ---> Researching Commands
**Lab 3** is about research commands and our teacher gave as to chose from these three commands those are 
*less, find, and grep*. and i choose grep command   
and with the help of grep --help command i found many interesting command-line options. and here i am   
going to show you 2 examples using 4 grep commands.  

![image](https://user-images.githubusercontent.com/122564368/221768679-9fa2a75d-8d18-4c33-9bf2-926887223445.png)  



    To start with you have to downlod the file written_2 from the github and open it with your   
    Vscode. Then using the vscode bash you can use all the usefull grep commands.  
    

## grep -w  

The **-w** help us to Check for the whole words in a file by default, grep matches the given string/pattern even   
if it is found as a substring in a file. The -w option to grep makes it match only the whole words.  
let's see two examples using the grep -w command  

Here -w flag is used to output all those lines in .txt containing **day** as a whole word and not as a sub-string.
![image](https://user-images.githubusercontent.com/122564368/221748538-f610b731-18f3-42f2-bbf4-1d2a4d38aecb.png)  

 ***Lets have second example in different file.txt***  
 Here -w flag is used to output all those lines in Kauffman.txt containing **they** as a whole word and not as a sub-string.  
 ![image](https://user-images.githubusercontent.com/122564368/221750090-b9781f89-0391-4be8-8f58-e9f7f9374445.png)  
 ---> So from this two examples we learned that **-w** is used to check the given word in whole words not in sub string.
 
 ## grep -o
 The **grep -o** used to display only the matched pattern. this grep displays the entire line which has the matched string only.    
 unlike the grep -w the grep -o flag displays only the matched pattern instead of displaying the entire string or line which   
 contains it.let's see what is the exact difference with the grep - w command using the same examples and the same file.txt.  
 
  --> Here -o flag is used to output all those lines in Kauffman.txt containing **they**.  
 
 ![image](https://user-images.githubusercontent.com/122564368/221752197-4d5d27ee-13fc-4261-8d97-279fbbbd405a.png)  
 
  And the Second example from the .txt file is  
  
  --> Here is -o flag is used to output all those lines in Abernathy.txt containing **day**.
  
  ![image](https://user-images.githubusercontent.com/122564368/221752591-2b9cc39c-183c-42bc-ba3b-19c05afe0364.png)  
  
## grep "^"  

   The grep "^" matching the lines that start with the given string. The ^ regular expression pattern specifies the  
   start of a line. This can be used in grep to match the lines which start with the given string or pattern.  
   
   --> Here ^"Trade" flag is used to output all those strings that started with Trade in Abernathy.txt.  
   
   ![image](https://user-images.githubusercontent.com/122564368/221754994-10811d6b-8aae-4897-85fa-d607a8ff4835.png)  
   
  --> And here "^So" flag is used to output all those strings that started with So in Kauffman.txt.
    
   ![image](https://user-images.githubusercontent.com/122564368/221755437-0d11f7ed-5689-46ed-baf2-9559ef4016c8.png)  
   
## grep -c  
    
      The grep -c is used to find the number of lines that matches the given string/pattern   
      
     --> Here we used the grep -c to find the number of "does" strings in Abernathy.txt.  
      
    
  ![image](https://user-images.githubusercontent.com/122564368/221761583-11783874-9708-40d8-8960-966d4fc06d71.png)  
    
    
     ----> Here we used the grep -c to find the number of "is" strings in Abernathy.txt..
      
       
 ![image](https://user-images.githubusercontent.com/122564368/221761741-28d7beb7-418a-47f9-836e-6b6ad2c0f47b.png)  
 
 



## ChatGPT
                    **Here is some explanation of chatgpt about how grep works**  
       
 ![image](https://user-images.githubusercontent.com/122564368/221764894-c92feaea-d783-44d4-b853-e192346b47c6.png)  
 
 ![image](https://user-images.githubusercontent.com/122564368/221764996-a139ab5b-bcee-474d-a16b-8ddc4759438b.png)





  
  
  
  

  

 




