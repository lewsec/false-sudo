# false-sudo
make sudo appear as installed but will execute su commands as regular user

## Install
if you have sudo already installed.. 
*Remove it* or rename it.  
Clone the repo:  
```
git clone https://github.com/lewsec/false-sudo.git
```  
cd into the repo:  
```
cd false-sudo
```  
make sure the file is executable and move it to the `/bin`:  
```
chmod a+x ./sudo.sh && mv ./sudo.sh /bin/sudo
```
should be it.
