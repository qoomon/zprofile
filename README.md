# zprofile

## install
### [zgem](https://github.com/qoomon/zgem)
```zgem bundle 'https://github.com/qoomon/zprofile.git' from:'git' use:'zprofile.zsh'```
### manually
```
git clone https://github.com/qoomon/zprofile.git
source zprofile/zprofile.zsh
```

## Adjust .zshrc
```
if [ "$ZPROFILE" = 'active' ] ; then zprofile::before; fi

# SCRIPT TO PROFILE 
# ...

if [ "$ZPROFILE" = 'active' ] ; then zprofile::after; fi
```

### usage
| command                   |
|---                        |
|`zprofile`                 |
|`zprpfile benchmark`       |
|`zprofile <FUNCTION_CALL>` |
