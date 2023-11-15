# Scripts 

## work
### description
a more convinient commant than `cd`.we can use it to go to the path of our workspace more easily.

### usage
- with no args:`source work` go to the root path of our workspace.
- with args:`source work temp`go to the path of `temp` which is the subdir of our workspace.

### environment 
the key word `USERS_PATH` is the path of our workpath.


## ghub
### description
a script to get a user's repos on github.there are two kind of url we can get,`ssh_url`&`https_url`.

### usage
- with command `ghub -ssh`,we will get the ssh type url. 
- with command `ghub -https`,we will get the https url.

### environment
the `USERS` key word is custom setting represent the github username.

## m-sym
### description
generating mathml type results while using sympy to calculate.

### usage
- just write the code in userspace and put the result string into the string list,then the html file will generate in the workspace path.
