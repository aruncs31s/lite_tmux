
### ***Requirements***

```
git tmux
```

### ***install***
### 

```
cd
git clone https://github.com/aruncs31s/lite_tmux/ 
mv ~/.tmux.conf ~/.tmux.conf.bak
cp ~/lite_tmux/.tmux.conf ~/.tmux.conf
```


![alt text](https://github.com/aruncs31s/lite_tmux/blob/main/.img/Screenshot%20at%202022-02-16%2001-19-25.png)


### Keybindings 

- resise the panes(windows)
```
bind-key J resize-pane -D 5
bind-key K resize-pane -U 5
bind-key H resize-pane -L 5
bind-key L resize-pane -R 5

```
- To hide and show status
```
bind-key u set status off
bind-key U set status on

```
- Switch Windows

```
bind -n S-Left  previous-window
bind -n S-Right next-window
```

