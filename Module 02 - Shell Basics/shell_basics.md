# What is a shell
Command line interpreter

A shell figures out
- What command
- What options 
- What arguments

## Functions of a shell
- expand wildcards
- redirect input and output 
- group commands
- interpret command line
- expand shell variables
- interpret aliases
- process shell scripts

## Reserved words
- case, do, done, elif
- else, fi, for, if
- function, in, select, then
- until, while

### Wildcard expansion
- Single Character
```sh
    ls ne?
```

- Multiple Characters
```sh
    ls n*
```

- Value list
```sh
    ls ne[stw]
```

- Range
```
    ls *[1-5]
```

- Not (Not-inclusive)
```sh
    ls [!tn]*
```

### Output redirection 
- `>` - Overwrite
- `>>` - Append

Example
```sh
    ls -l > filelist
    ls -l >> filelist
```

### Using pipes (|)
```sh
    ls -l /dev | more
    cat filelist | less
```