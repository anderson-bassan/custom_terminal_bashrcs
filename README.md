![Print screen of my terminal showing the styles for root and regular user](custom_terminal_print.png?raw=true "Custom Terminal")

# Custom Terminal Bashrcs
Files to customize the terminal for regular and root user

## INSTALL
To install the files to the curent user and the root as regular user:
```
$ git clone https://github.com/anderson-bassan/custom_terminal_bashrcs.git
$ cd custom_terminal_bashrcs
$ mv .bashrc ~/
$ sudo mv .bashrc_root /root/.bashrc
$ ../ && rm custom_terminal_bashrcs
$ source ~/.bashrc
$ sudo source /root/.bashrc
```
  
If you have more than one regular user copy these .bashrc to the other users home
