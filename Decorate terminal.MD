## Decorate terminal
1.  Open ```.bash_profile```
    ```
    if [ -f ~/.bashrc]; then
        source ~/.bashrc
    fi    
    ```
    
1.  Open ```.bashrc``` file
    ```
    PS1="Custom-> ";
    ```
    ```Custom``` can be any thing you want to add
    
    eg: ```\u``` the username of the current user
       
        \n new line
        
        \s the name of the shell
        
        \h the hostname up to the first
        
        \t the current time in 24-hour format
        
        \w the current working directory
        
        \W the basename of the current working directory
        
        
        
