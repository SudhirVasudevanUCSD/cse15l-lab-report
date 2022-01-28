#1st Issue
Code Change Diff:
![img1](Lab%20Report%202%20Images/Issue%20%231.JPG)
Test File that prompted change: <a href="test-file2.html" download>test-file2.html</a>
<br />
<br/>
Symptom Output: 
![img2](Lab%20Report%202%20Images/Symptom1.JPG)
<br />
Description: The initial code doesn't have a way to distinguish
between image or regular links(which is the bug). So when tested on a faulty
 inducing input file with just an image location, the code incorrectly
  returns the image location as a "link" as seen in the symptom output.
<br/>

#2nd Issue       

<br/>  

Code Change Diff:
![img3](Lab%20Report%202%20Images/Issue%20%232.JPG)
Test File that prompted change: `No File Case`
<br />
<br/>
Symptom Output:
![img4](Lab%20Report%202%20Images/Symptom2.JPG)
Description: The initial code doesn't have a way to handle a no file input or
 in other words, it assumes that the run will always have at
  least one command line argument(which is the bug). So when tested on a faulty
 inducing input by running the command "java MarkdownParse" without any
  arguments, the code incorrectly handles the case by throwing an
   ArrayIndexOutOfBounds Exception as seen in the symptom output.  

<br/>

#3rd Issue  

<br/>

Code Change Diff:
![img3](Lab%20Report%202%20Images/Issue%20%233.JPG)
Test File that prompted change: <a href="test-file.html" download>test-file.html</a>
<br />
<br/>
Symptom Output:
![symptom](Lab%20Report%202%20Images/Symptom3.JPG)
Description: The initial code assumes there will be atleast one open bracket
("[")(which is the bug). So when tested on a faulty inducing input file with
 just a string of numbers, the code incorrectly throws a
  StringIndexOutOfBounds Exception as seen in the symptom output.