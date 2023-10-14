# jrnl
Fuzzy search & copy a command from your shell history

## Usage:
1. Put `jrnl` file in your PATH
2. Execute `jrnl` or add a keybinding in your `.zshrc`
```
_jrnl () { echo; jrnl; zle redisplay }
zle -N _jrnl                  
bindkey "^j" _jrnl #Bind Ctrl-J
```

https://github.com/artieeg/jrnl/assets/60566430/6788f7ac-b8c7-4d75-825b-4d8d3543bef9
