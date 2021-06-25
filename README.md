# Change-Terminal-Mac-color and other appereance customization A to Z
### => Change Terminal Mac color text and fond
### => install zhs for Terminal Mac color
### => install zhs for Terminal Mac color
### => add autocompletion by adding vi zhs plugins
.
.

To change the terminal color to differentiate the folders and files, use mentioned commands:

  ```sudo vim ~/.bash_profile```

add the codes inside the empty bash file 

 ```export CLICOLOR=1```
 
 ```#PS1='[\u@\h \W]\$ ‘  # Default```
 
 ``` PS1=’\[\e[1;32m\][\u@\h \W]\$\[\e[0m\] ```
 
 esc +  ":"
 then write "wq" to save the changes in the file. 
 
 if you want to have a different color for the folders and file while doing "ls":
 ```
 alias ls='ls -G'
 alias ll='ls -lG'
 ```
 
 Then write "wq" to save the changes in the file. 
 If you have installed zhs: 
 
 ```
  sudo vi  ~/.zprofile
  
```
 
To change the background, open preferences on the top left corner of your terminal.
  
<img src="https://user-images.githubusercontent.com/17232450/122657406-995e6580-d163-11eb-9c89-eeea55618daa.png" width= "690px">

To change the font size: 


![Screenshot 2021-06-25 at 11 23 43](https://user-images.githubusercontent.com/17232450/123406089-d5058f00-d5aa-11eb-9526-dc1474267ed1.png)

  
Hope you enjoy your colorful terminal!

close and open the terminal again, and if it doesn't work, try this :
https://www.cyberciti.biz/faq/apple-mac-osx-terminal-color-ls-output-option/

If you would like to have more features like auto-complete install Zhs: 

https://www.howtogeek.com/362409/what-is-zsh-and-why-should-you-use-it-instead-of-bash/

![Screenshot 2021-06-25 at 10 28 00](https://user-images.githubusercontent.com/17232450/123395220-3e33d500-d5a0-11eb-9174-10b3b11f8d05.png)


# Change-Terminal-VS-CODE 
press 
in Mac command + p 
in win ctrl + p

search for setting.json
