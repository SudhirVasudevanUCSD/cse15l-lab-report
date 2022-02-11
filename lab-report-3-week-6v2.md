#Copying whole directories with scp-r

##Copying markdown-parse directory into ieng6 account
![img1](Lab%20Report%203%20Images/%231.JPG)
...More lines of files shown being copied  

<br/>

Using the recursive setting with `scp -r`, we can copy over the entire
 markdown-parse directory in one line. Instead of having to individually copy
  over 199 files, we can just use one command to copy over the whole
   directory.  
   
   <br/>

##Logging into ieng6 account, compiling, and running tests 
Logging in:
![img2](Lab%20Report%203%20Images/%232.JPG)
Compiling and running MarkdownParseTest:
![img3](Lab%20Report%203%20Images/%233.JPG)  
<br/>
We can use the `ssh` command to login to our course specific account. Then
 using the `ls` command, we can verify that the markdown-parse directoroy
  got copied over. Then we use `cd` to navigate to that directory and then
   use the specific j-unit commands to compile then run the code.  
   
   <br/>
   
##Optimized running

Although the above method isn't a bad way to copy over a whole directory
, then run the code in it. Using some tricks we can simplify this process
 even more to run in just one line, like shown in the following:
 ![img4](Lab%20Report%203%20Images/%234.JPG) 

