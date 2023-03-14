## Lab Report 4
  For the lab report we are going to reproduce the task from the week seven lab competition on our own. For each step   
  starting right after the timer 4-9 we are going to take a screenshot and explain it step by step and write down  
  exactly which keys we pressed to get to that step.  

##  Step 1  
  The first step is to launch the terminal or VScode terminal, and then to open bash.   
  While inside bash, you type ssh cs15lwi23app@ieng6.ucsd.edu to log onto the remote   
  computer.For me becouse i allready typed it befoure i just have to press the "^" up   
  key and Enter when i got my ssh...  

![image](https://user-images.githubusercontent.com/122564368/224811912-b756c1bf-6922-45c2-a178-987a5a101afb.png)    

## Step 2  
  The second step is simple, all you have to do is clone the provided document lab7 by   
  copying from your repository link as shown below and by pressing (control + V) or paste  
  it into your bash program after typing git clone.  

![image](https://user-images.githubusercontent.com/122564368/224840086-0229e369-23c6-407d-b59d-6ea4c3a42cf3.png)  
  
**----->   *And here is the result from my bash terminal***    
             
![image](https://user-images.githubusercontent.com/122564368/224821304-b4f30d12-c4f5-49aa-84cd-a5d2adf4914b.png)  

## Step 3  

   After cloning, you can view the documents in the Lab7 folder by typing "ls" and then   
   pressing Enter. this will exicute the files inside the lab7 folder and now we must   
   execute the provided Java application to determine whether our code contains any errors   
   or not by copping and pesting this two provided commands.  

      javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java 
      java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore   
      ListExamples.java  
      
  
 As you can see from the code below, there is one failure, so we must use nano text editor to correct  
 the problem below. GNU nano is a simple terminal-based text editor. Though not as powerful as Emacs   
 or Vim, it is easy to learn and use   
 
![image](https://user-images.githubusercontent.com/122564368/224822105-54777ce8-2b86-4e91-8a7f-28e89918c587.png)    

## Step 4
  In order to use the text editor and fix the issue as the image below, we must first type nano,   
  then the name of the java document we want to use. In order to add, I typed nano L and <tap>,  
  and the word ListExamples was automatically filled in. and I added ".java" at the end of the  
  text editor then I was able to obtain the complete code as seen below.  

  To fix the code you have to scroll down using the down arrow key until you reach the error. the error is in the last while  
  loop that was by mistake saying index1 and you have to change it index2 and then "Ctrl o" Enter to save it and "ctrl x" to exit.  
    
![image](https://user-images.githubusercontent.com/122564368/224822451-4da53cff-d13e-4c4d-8e5f-d84c124c7094.png)
![image](https://user-images.githubusercontent.com/122564368/224888597-8e27be9f-15cc-47a2-b86e-6250fcf080d2.png)

        To get the command below <up><enter>  
        javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java  
        and then <up><up><enter>  
        java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore  
        TestListExamples   
  

**----->  And now we have to run the junit tester command again to see whether the error is fixed or not**  
**----->  So as we see below we dont have any errors now**   

![image](https://user-images.githubusercontent.com/122564368/224908549-a5a7ba1d-e551-4e98-ba41-c29faf301427.png)

        
        
## Step 5
    Last but not least, we must commit and send the resulting update to our Github account.   
    To start, I used git add. I then used git commit -m to commit my changes together with  
    the specified message. I afterwards uploaded my changes to my Github account using git push.  

![image](https://user-images.githubusercontent.com/122564368/224834004-dff01e43-a066-4ad6-929f-3ebad3b1a3b7.png)

