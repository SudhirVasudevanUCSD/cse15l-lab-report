#Tests  

<br />


##How I found the tests  

<br />


I used the ```diff``` on the results of the running of the following bash script
 ```for``` loop  
 
 <br />
 

![img1](Lab%20Report%205%20Images/bash.JPG)  

<br />

##Test #1  

![img2](Lab%20Report%205%20Images/Case928.JPG)  

<br />

Corresponding test file: 516.md.
![img4](Lab%20Report%205%20Images/File516.JPG)  

<br />

Only my interpretation was correct because there is no correct url in the
 picture and my interpretation returned no link while the given
  interpretation returned ````moon.jpg````.   

<br />
 
Bug in the given code:
![img5](Lab%20Report%205%20Images/img1.JPG)  

<br />


This method doesn't do anything to check whether the text in between the
 parentheses is actually a link or a file name and just automatically returns
  the text as long as it follows the parentheses description. 
  An easy way to fix this for this test case is to provide a check for the
   exclamation mark that is before an image file description in markdown
    language.   
   

<br />


##Test #2  

<br />

![img3](Lab%20Report%205%20Images/Case884.JPG)
Corresponding test file: 472.md
![img6](Lab%20Report%205%20Images/File497.JPG)
My interpretation was correct because as verified by CommonMark, the correct
 url in the picture is ```foo\(and\(bar\))``` and my interpretation returned 
 that output while the given interpretation returned no link found. 
  
 Bug in their code:
 ![img5](Lab%20Report%205%20Images/img2.JPG)
The bug is that as we see in this line, the given implementation only
 determines something is a link if there is a ``.`` in it. However, this
  idea ignores the fact that "links" can actually be path destinations. 
  So the fix would be to remove this feature and simply return what is in
    between the matching outer pairs of parentheses, which is what My Code does.
