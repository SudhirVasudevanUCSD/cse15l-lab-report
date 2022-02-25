#The Tests:  

[My Repo](https://github.com/SudhirVasudevanUCSD/markdown-parse)  

<br/>

[Reviewed Repo](https://github.com/pvijay03/markdown-parse)  

<br/>

##Snippet 1  

<br/>

### Expected Output:    

![img1](Lab%20Report%204%20Images/%231.JPG)  

<br />

### Code Test:  
![imgTest1](Lab%20Report%204%20Images/Test1.JPG)
<br />

### My Implementation's Output:  
![myImplementation](Lab%20Report%204%20Images/MyImplementation.JPG)
As seen in the image, testSnippet1() failed, meaning this test failed in my
 implementation.  
 
<br />

### Reviewed Implementation's Output:  
![reviewed](Lab%20Report%204%20Images/Reviewed.JPG)
As seen in the image, testSnippet1() failed, meaning this test failed in the
reviewed implementation.  
 
<br />


#Snippet 2  

<br />

### Expected Output:     

![img2](Lab%20Report%204%20Images/%232.JPG)  

<br />

### Code Test:  
![imgTest2](Lab%20Report%204%20Images/Test2.JPG)  

<br />

### My Implementation's Output:  
![myImplementation](Lab%20Report%204%20Images/MyImplementation.JPG)
As seen in the image, my implementation passed as there was no errors for the
 testSnippet2() method.  
 
<br />

### Reviewed Implementation's Output:  
![reviewed](Lab%20Report%204%20Images/Reviewed.JPG)
As seen in the image, testSnippet2() failed, meaning this test failed in the
 reviewed implementation.  
 
<br />


#Snippet 3  

<br />

### Expected Output:  
![img3](Lab%20Report%204%20Images/%233.JPG)  

<br />

### Code Test:  
![imgTest3](Lab%20Report%204%20Images/Test3p1.JPG)  
![imgTest3](Lab%20Report%204%20Images/Test3p2.JPG)    

<br />

### My Implementation's Output:  
![myImplementation](Lab%20Report%204%20Images/MyImplementation.JPG)
As seen in the image, testSnippet3() failed, meaning this test failed in my
 implementation.  
 
<br />

### Reviewed Implementation's Output:  
![reviewed](Lab%20Report%204%20Images/Reviewed.JPG)
As seen in the image, testSnippet3() failed, meaning this test failed in the
 reviewed implementation.  
 
<br />

## Questions:
For Snippet 1, one (<10 lines) solution is to just stop considering all back
 ticks after the first "()" link bracket because that's what Common mark
  considers as just part of the link. That way only the text that shows of a
   link could be altered, not the link itself.
  
For Snippet 2, it would be a more involved solution because we would have to
 deal with multiple edge cases of nested parentheses/brackets and escaped
  bracket cases because of the various combinations that could occur. These
   combinations would constitute multiple if statements/loops which would
    result in a solution longer than 10 lines.
    
For Snippet 3, it would be possible to do a (<10lines solution) by just making
 sure there aren't any breaks in the text or link as Common Mark doesn't seem
  to consider any breaks to be in proper line format. Anything with line
   breaks should just be treated as pure text per Common Mark's guide.

<br />