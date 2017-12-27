# zprofile

## install

#### .zshrc
```
source zprofile.zsh
if [ "$ZPROFILE" = 'active' ] ; then zprofile::before; fi

SCRIPT TO PROFILE 

if [ "$ZPROFILE" = 'active' ] ; then zprofile::after; fi
```

### usage
| command                   |
|---                        |
|`zprofile`                 |
|`zprpfile benchmark`       |
|`zprofile <FUNCTION_CALL>` |
