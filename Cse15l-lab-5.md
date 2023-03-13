# Lab Report 5
**For lab report 5 I decided to look at lab report 3 (regarding find/grep, etc.) , working on various 
choices for a different command or commands.**  
**We have discussed -W, -O, "^", and -C in my lab report 3, and now we will discuss other commands for grep   
  (-i,-h,,-H,,-l,-L) and the grep search pattern.**

## 1, grep -i
  A case-insensitive search is ensured by the grep -i is option. No matter the alphabetical case, it shows as a string or sub-string   
  all the lines in file.txt that contain the word THe. For instance, in lab 3 we saw an example of how to use -c, now let us  
  compare the two.  

##        Example 1
  ![image](https://user-images.githubusercontent.com/122564368/224576059-1320292a-3a3a-476a-aef7-42a03b73546d.png)
  
  The useful option -i gives you an accurate count because it ignores case, as seen between commands one and two above.  
  Let us say you wanted to count how many times string "The" was used in Ch1.txt. The grep -i command enables us to locate  
  the text regardless of the alphabetical case because, as we can see above, the first count was 58 and the second count was 126.

##        Example 2
![image](https://user-images.githubusercontent.com/122564368/224576488-1e449427-6598-4b83-8a39-f40e9a0942e1.png)
![image](https://user-images.githubusercontent.com/122564368/224576512-1d03e48a-dd50-4c3b-81c4-a9d310d21d76.png)
![image](https://user-images.githubusercontent.com/122564368/224576559-32880b95-f1f0-4eca-9562-d2ed40e763f8.png)
 
The word "THe" was located using the grep -o option, as seen in example 2, and only the matching pattern was displayed.   
This grep only shows the complete line that contains the matching string. Because of this, when we add grep -i,   
we can see that it allows us to find the text independent of the alphabetical case.   

## 2, grep -h and -H
  I come to understand the distinction between -h and -H after lab 3. When using grep on numerous files, the 
  -h option by default displays the name of the file where the match was discovered. Even if you grep from a 
  single file, the file name will always be displayed if you enter -H. The -h option can be used to hide the 
  file name.

##        Example 1
![image](https://user-images.githubusercontent.com/122564368/224578564-c64855a8-aff1-4605-82e9-afc3239c08a5.png)

![image](https://user-images.githubusercontent.com/122564368/224578584-9eb1e088-c740-4fc2-a75f-5f787a416526.png)

## 3, grep search with other patterns 
   grep searches provided input files, identifying lines that fit one or more patterns.With   
   either the -c or other option, you can define the order to look for. If neither option is   
   specified, grep uses the first non-option argument as the pattern to look for then When  
   grep discovers a line that matches a pattern, the complete line is shown. let see the two   
   examples of grep with no pattern and grep -c pattern. 

##        Example 1  
 ![image](https://user-images.githubusercontent.com/122564368/224580897-f1ee5a4a-ef44-4f55-902d-8c58ef96fa1b.png)

##        Example 2
 ![image](https://user-images.githubusercontent.com/122564368/224580934-492aa626-78c4-4fbe-af34-7c7a304392d9.png)
 
 From these two examples, we can decide that when using grep search, it is best to specify what you are 
 looking for by including additional patterns like -c, -i, -w, etc. If you attempt to search without any 
 help patterns, you might find yourself with a large number of results. 

## 4, grep -l and -L  
 
      The grep -L uses to print only names of FILEs containing no match and   
      The grep -l uses  to print only names of FILEs containing matches
      
   As you can see below, -L only prints those filenames that do not contain matches, for example  
   in the second example the output is nothing because all the txt files have the word "The", but   
   in the first example the word "Man " is not found in ch5 .txt and ch9. txt unlike -l can only  
   print files that contain the given word  

##        Example 1
![image](https://user-images.githubusercontent.com/122564368/224582307-b061bc6c-19e4-4d9f-8c13-b5a7666b425f.png)
![image](https://user-images.githubusercontent.com/122564368/224582344-2bf41700-e951-4605-88c3-1954644bc13c.png)

##        Example 2
![image](https://user-images.githubusercontent.com/122564368/224582401-17cd99c9-46cc-417e-8a41-4132892217cf.png)














 
  

 

