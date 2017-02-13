# P(u)shit

> a `cp` helper   

### Setup   

1. download **pshit**   

2. enter directory, and copy script to new
```
cd pshit && cp pshit pshift-dev
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


