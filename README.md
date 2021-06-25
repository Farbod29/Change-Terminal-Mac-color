# Change-Terminal-Mac-color
Change Terminal Mac color

to change the terminal color to differentiate the folders and files use mentioned commands:

  ```sudo vim ~/.bash_profile```

add the codes inside the empty bash file 

 ```export CLICOLOR=1```
 
 ```#PS1='[\u@\h \W]\$ ‘  # Default```
 
 ``` PS1=’\[\e[1;32m\][\u@\h \W]\$\[\e[0m\] ```
 
 esc +  ":"
 then write "wq" to save the changes in the file.
 
 
To change the backgroungd open prefences on top left corner of your terminal.
  

  <img src="https://user-images.githubusercontent.com/17232450/122657406-995e6580-d163-11eb-9c89-eeea55618daa.png" width= "690px">

Hope you enjoy your colorful terminal !

close and open terminal again, and if it doesnt work try this :
https://www.cyberciti.biz/faq/apple-mac-osx-terminal-color-ls-output-option/

If you would like to have more fetures like auto compelete: 
https://www.howtogeek.com/362409/what-is-zsh-and-why-should-you-use-it-instead-of-bash/

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

