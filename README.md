# Utility Bash Scripts
This repository contains some of the useful bash scripts I use in my daily workflow.

## My Usage
- Clone this directory to some custom path.
- I want to use a path in my `~` directory so I create a symbolic link to the custom path:  
    `ln -s custompath/bin ~/bin`
- Edit my `~/.zshrc` to add a line at the end of the file:      
    `export PATH=$PATH:~/bin`.
- Run `source ~/.zshrc` in my currently open terminal.
- Try a script out in the terminal - say run `git lazycommit "Added some scripts."`.


## Adding a New Script
- Add the script in `./bin`.
- Run `chmod +x script-name`.
