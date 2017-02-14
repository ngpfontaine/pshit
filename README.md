# P(u)shit

> a `cp` helper   

## Setup   

- Clone **pshit** wherever you want (`~/` in this example) and enter.
```
git clone https://github.com/ngpfontaine/pshit.git ~/ && cd ~/pshit
```   

- Open in editor and change pathing variables with your intended paths, then save.
```
vim pshit   
   
baseDir='~/example'
targetDir='/var/www/example.com/public_html'
```   

- Make it executable.
```
chmod +x pshit
```   

- Create a symlink to your new **pshit** in root **/bin**.
```
sudo ln -s ~/pshit/pshit /bin/pshit
```   

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

- argument for switching **base** & **target** directories w/o having to make a new **pshit**   

- deal with subdirectories   
