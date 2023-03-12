# Lab Report 5
**For lab report 5 I decided to look at lab report 3 (regarding find/grep, etc.) , working on various 
choices for a different command or commands.**  
in my lab report 3 we have seen about -W, -O, "^", -C and now we will see diffrent comannds on gerep -i,-h

## grep -i
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





 
  

 

