# P(u)shit

> a `cp` helper   

### Setup   

- download **pshit**   

- enter directory
```
cd pshit
```   

- copy script to new
```
cp pshit pshit-dev
```   

- edit
```
vim pshit-dev
```   

- modify `baseDir` & `remoteDir` to your source & receiving directories respectively
```
baseDir='/example/local/path'
remoteDir='/example/remote/path'
```   

- make executable
```
chmod +x pshit-dev
```   
- create symlink in **/bin**
```
sudo ln -s ~/example/path/pshit-dev /bin/pshit-dev
```   

### Use   

list **help** info
`pshit-dev --help`   


