# Linux Commands
```
    $ command options arguments
```

Examples
- ls
- ls -l
- ls /dev
- ls -l /dev

*Linux commands are case-sensitive*

# Notes about the syntax
- Multiple options are preceded by One minus sign
```
    ls -alt
```

- Or separated by spaces
```
    ls -a -l -t 
```

- Help available for many commands
```
    ls --help
    man ls
```

# Linux process commands
- exit
- logout
- passwd
- ssh
- ftp  
- ctrl-d (End current process)

## The passwd command
```
passwd
Changing password for tux1
Old password:
New password:
Retype new password:
```

## Linux file commands
- cat
- cp 
- rm 
- less
- mv

## Editing files
```
    cat > filename
    abc
    xyz
    ^C
```

*OR*

```
    vim filename
    nano filename
```

## Directory commands
- cd 
- mkdir 
- pwd
- rmdir
- rm
- ls

## Linux special files
- Hardware Devices Eg. `/dev/lp0`
- Logical devices Eg. `/dev/null`

## File naming conventions 
Alphabetic characters (Case-sensitive)
    - upper case
    - lower case
Numbers
@_(Other specials also allowed)
No blanks
May not begin with + or - 
Case-sensitive
Files are hidden if they start with a .
255 characters max