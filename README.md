# P(u)shit

> a `cp` assistant      
   
   
## Setup   

- Clone **pshit** wherever you want ( ` ~/ ` in this example) and enter.
```
git clone https://github.com/ngpfontaine/pshit.git ~/pshit && cd ~/pshit
```   

- Make it executable.
```
chmod +x pshit
```   

- Create a symlink to your new **pshit** in root **/bin**.
```
sudo ln -s ~/pshit/pshit /bin/pshit
```   

- Run setup. You will be prompted to enter your  **base** & **remote** paths.
```
pshit --setup
```   

- Now **pshit** will copy files from `~/example/` > `/var/www/example.com/public_html/` (**note:** sudo will be invoked). Run ` pshit --setup ` anytime to change it's functionality.   

## Use   

List **help** info   
`pshit --help`   

**pshit** everything   
`pshit --all`   

Files in main directory   
`pshit --files`   

One file, in main directory   
`pshit index.html`   

A recursive directory in main dir   
`pshit css`   

## To-Do   

- create symlink during **--setup**. need to get path of script as var

- deal with subdirectories   


