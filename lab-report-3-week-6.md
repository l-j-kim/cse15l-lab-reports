Lab Report Week 6
====

Streamline ssh Configuration
---
To help streamline ssh configuration, a config file was created and edited as shown below so that the file contained the host name, my username, and a reference to the ssh key for my password. 
![image](lab-report-3/config-file.png)

This made it so that logging in to ieng6 would by easier. For example, instead of having to type in `$ ssh cs15lsp22aaw@ieng6.ucsd.edu`, I can just type in `ssh ieng6`, and log in. This can be seen by the screenshot below.
![image](lab-report-3/new-login.png)

Additionally, copying files from my computer to the server is also much simpler. Like before, I only need to type in `scp HelloWorld.java ieng6:` instead of `scp HelloWorld.java cs15lsp22aaw@ieng6.ucsd.edu:~/` as shown below, and when logging into the server afterwards, the copied file can be seen by typing `ls`.
![image](lab-report-3/scp-config.png)

Set up Github Access from ieng6
---

Copy Whole Directories with scp -r
---