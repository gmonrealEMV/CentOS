What is this and what is it for ?
  As  you probably know, 'CentOS 8' has gone EOL, end of life, and is no longer supported. So, that leaves us with the question, so... now what ?
    You could upgrade 'CentOS 8' to 'CentOS Stream', but keep in mind that 'CentOS Stream' is not considered stable since it is considered as constantly in development.
      And what does "constantly in development" mean ?
        It means, there might be bugs and a user of 'CentOS Stream' is expected to acknowledge that fact. Sure, on your home PC that may not matter as too much but you 
          wouldnt want an unstable OS running in production.
        
You could use a stable version instead like Fedora or Ubuntu. But like many of you, I personally like CentOS and would like to keep using a stable version of it.
  If you didnt already know, that is basically what 'Rocky Linux' promises.
  
There is a script that was created to update CentOS 8 to Rocky Linux and could be obtained by simply running the command beloa:
"sudo git clone https://github.com/rocky-linux/rocky-tools.git"
 
If you have 'git' installed on your linux machine, thene "Congratulations", you are preaty much done, just follow the direction in that github account.

----HOWEVER ----
If you are here, at this github repository, then it is likely you dont have 'git' installed and probably got some kind of error message like "Failed to download 
metadata for repo 'AppStream'" when you tried to install 'git'.

  Why ?
    This is because CentOS 8 is EOL, and the servers that were being used to support it were brought offline. Luckly, you can still install utilities using the 'Vault archive' 

  How ?
    
