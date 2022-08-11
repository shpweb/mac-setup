PATH Backup (having java, brew in echo $PATH)  
.zshrc backup (simple zshrc)  
.zshrc backup with oh-my-zsh  
zsh-autosuggetions  

[MacOS connection keepalive for ssh <remote host>](https://rick.cogley.info/post/mac-osx-terminal-ssh-connection-keepalive/)
### How Do You Fix a Disconnecting ssh?
- You just add some keepalive packet settings to your local ssh’s config file, located in **~/.ssh/config**.
```s
Host *
    ServerAliveInterval 30
    ServerAliveCountMax 2
```
