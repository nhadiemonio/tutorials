### How to format shell prompt

Update bash profile:
```
$ vim ~/bash_profile
```

Add the line:
```
export PS1="\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\][\w]\[\033[00m\] \$ "
```
