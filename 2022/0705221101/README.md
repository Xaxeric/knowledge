# How to get terminal width and heigth size in bash ?

To get terminal size can be done by using environment variable or `tput` command:

```bash
tput cols # Get terminal width
tput lines # Get terminal height
```

Or by using environment variable:

```bash
echo "${COLUMNS}" # Get terminal width
echo "${LINES}" # Get terminal height
```

## Related:

- https://www.codegrepper.com/code-examples/shell/get+terminal+size+linux
- https://stackoverflow.com/questions/263890/how-do-i-find-the-width-height-of-a-terminal-window

## Tags:

    #bash-scripting #methods
