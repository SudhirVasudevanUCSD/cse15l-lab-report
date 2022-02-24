#Streamlining ssh Configuration

## ```.ssh/config``` file
![img1](Lab%20Report%203%20Images/GitBash.JPG)
My computer already had a .ssh directory but the config file wasn't yet, so I
 had to create it. I navigated to the .ssh directory and right clicked, to get
  the "Git Bash Here" option emulating to get a git-like command line. Then I
   ran the commands "touch config" and "nano config" to create and then open
    the config file. Then as seen in the picture, I just typed up the lines
     specified in the lab with my username and chosen alias.  
     
<br/>

## ssh command

![img2](Lab%20Report%203%20Images/Login%20with%20SSH.JPG)
After creating the config file, I tried to login with the alias "ieng6" that
 I had chose. As seen in the picture, it worked, and logged me in as if I had
  used my account itself.  
  
  <br/>
  
## scp command
![img3](Lab%20Report%203%20Images/SCP.JPG)
As seen in the image, I used the scp command on file, "MyArrayList.class
" with the alias I had chosen. Then to verify the file got copied over, I
 logged into the server with my account and when I did ls, I saw that the
  file made it there.