# Change-Terminal-Mac-color and other appereance customisation A to Z
### => Change Terminal Mac color text and fond
### => install zhs for Terminal Mac color
### => install zhs for Terminal Mac color
### => add autocompletion by adding vi zhs plugins
.
.

to change the terminal color to differentiate the folders and files use mentioned commands:

  ```sudo vim ~/.bash_profile```

add the codes inside the empty bash file 

 ```export CLICOLOR=1```
 
 ```#PS1='[\u@\h \W]\$ ‘  # Default```
 
 ``` PS1=’\[\e[1;32m\][\u@\h \W]\$\[\e[0m\] ```
 
 esc +  ":"
 then write "wq" to save the changes in the file. 
 
 if you want to have diffrent color for the folders and file while doing "ls":
 ```
 alias ls='ls -G'
 alias ll='ls -lG'
 ```
 
 then write "wq" to save the changes in the file. 
 if you have installed zhs: 
 
 ```
  sudo vi  ~/.zprofile
  
```
 
To change the backgroungd open prefences on top left corner of your terminal.
  
<img src="https://user-images.githubusercontent.com/17232450/122657406-995e6580-d163-11eb-9c89-eeea55618daa.png" width= "690px">

To change the font size: 


![Screenshot 2021-06-25 at 11 23 43](https://user-images.githubusercontent.com/17232450/123406089-d5058f00-d5aa-11eb-9526-dc1474267ed1.png)

  
Hope you enjoy your colorful terminal !

close and open terminal again, and if it doesnt work try this :
https://www.cyberciti.biz/faq/apple-mac-osx-terminal-color-ls-output-option/

If you would like to have more fetures like auto compelete install Zhs: 
https://www.howtogeek.com/362409/what-is-zsh-and-why-should-you-use-it-instead-of-bash/

![Screenshot 2021-06-25 at 10 28 00](https://user-images.githubusercontent.com/17232450/123395220-3e33d500-d5a0-11eb-9174-10b3b11f8d05.png)


# Change-Terminal-VS-CODE 
press 
in Mac command + p 
in win ctrl + p

serch for setting.json

copy:
 "workbench.colorCustomizations": {
    "terminal.foreground": "#3ad641",
    "terminal.background": "#2a2a2a"
  },
  
  <img src="https://user-images.githubusercontent.com/17232450/122657707-61a4ed00-d166-11eb-9a8f-3b1e4dc78217.png" width= "590px">

