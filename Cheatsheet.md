## View Small Text Files
```bash
cat <filename>
```

## View Files Using `less`
```bash
less <filename>
```
### Go Down     (`Space`)
### Go up       (`b`)
### Search      (`/<keyword>`)
### Next Match. (`n`)
### Exit        (`q`)

## Reset Terminal
```bash
reset
```

## Find File Type
```bash
file <filename>
```

## Open Image from Terminal
```bash
open <filename>
```

<img width="1143" alt="image" src="https://user-images.githubusercontent.com/45315180/112323664-abdb1700-8cba-11eb-8899-6684b6f04493.png">

## Create a file
```bash
touch <filename>
touch <filename> <filename1> <filename2> 
```

## Create and Edit a File
```bash
nano <filename>
```

## Create a directory
```bash
mkdir <directoryname>
mkdir <directoryname> <directoryname1> <directoryname2>
```

<img width="985" alt="image" src="https://user-images.githubusercontent.com/45315180/112326456-34f34d80-8cbd-11eb-9720-75977e847976.png">
<img width="1276" alt="image" src="https://user-images.githubusercontent.com/45315180/112326612-55230c80-8cbd-11eb-896c-b589e346ee33.png">
<img width="1216" alt="image" src="https://user-images.githubusercontent.com/45315180/112326782-7edc3380-8cbd-11eb-8587-9c92121285ab.png">

## Pipeing
Chaining commands (Output from command becomes input the other; **Right to Left**)
### View Files in currdir
```bash
ls | less
```

### Chaining examples
Finds rows with 1978 -> Sort them -> Write to file
```bash
grep 1978 <filename> | sort > 1978_files.txt
```

Find the count of movies with 4 oscares
Get the third column -> Find pattern (4) -> Count using wc (word count)
```bash
cut -f 3 <filename> | grep 4 | wc -l
```

### Grep Command
[Grep How To](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)

### Cut Command

### wc Command

## Wildcards (Placeholder to find patterns REGEX)

### Move all text files into a folder
Moves files ending in text to the text folder
```bash
mv *text text
```
### mv command
```bash
mv <source> <destination>
```

### List specific extension files
```bash
ls *pdf
```

## Change default editor
```bash
export EDITOR=nano
```
