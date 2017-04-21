# zprofile

## install

#### .zshrc
```
source zprofile.zsh
if zprofile::active; then zprofile::before; fi

SCRIPT TO PROFILE 

if zprofile::active; then zprofile::before; fi
```

### usage
| call                      |     |
|---                        |---  |
|`zprofile`                 |     |
|`zprpfile benchmark`       |     |
|`zprofile <FUNCTION_CALL>` |     |
