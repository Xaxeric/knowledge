# How to join the words of arrays together string as a separator in zsh ?
To do that we can use parameter expansion flag builtin zsh:

```bash
local -a MyArray=(apple banana cherry) # Example array
echo "${(j..)MyArray}" # Output the array without white space between items. Or you can specify string as separator
```
The output will be:

```
applebananacherry
```

## Related:

- https://superuser.com/questions/1098551/append-string-to-array-elements-and-join-them-in-one-expression
- https://zsh-manual.netlify.app/expansion

## Tags:

    #zsh-scripting #methods

