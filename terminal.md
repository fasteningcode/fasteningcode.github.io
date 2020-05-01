When you the permission issues

check the owner of folfer

```
ls -la folder
```

if it's root, set to $USER

```
sudo chown -R $USER /usr/local/lib/node_modules
```


Error when npm i
 Error: EACCES: permission denied
 
 ```
 Restore ownership of the user's npm related folders, to the current user, like this:

sudo chown -R $USER:$GROUP ~/.npm
sudo chown -R $USER:$GROUP ~/.config
 ```
