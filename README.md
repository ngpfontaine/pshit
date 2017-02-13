# P(u)shit

> a `cp` helper   

### Setup   

1. clone **pshit** wherever you want and enter
```
git clone https://github.com/ngpfontaine/pshit.git && cd pshit
```   

2. copy script to new - this will be dedicated to copying from 1 specific directory to 1 specific other
```
cp pshit pshit-dev
```   

3. edit pathing variables. save.
```
vim pshit-dev   
   
baseDir='/example/local/path'
remoteDir='/example/remote/path'
```   

4. make executable
```
chmod +x pshit-dev
```   

5. create symlink in **/bin**
```
sudo ln -s ~/example/path/pshit-dev /bin/pshit-dev
```   

### Use   

list **help** info
`pshit-dev --help`   


