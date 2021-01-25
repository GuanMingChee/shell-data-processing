# Basic Shell Scripting Command
## Bash

- to create a new file

```
touch <FILENAME>
nano <FILENAME>
pico <FILENAME>
```

- to move file

```
mv <FILENAME> "new_file_destination"
```

- to copy file

```
cp <FILENAME> <NEW_FILENAME>
```

## PowerShell

- to create a new item

```
ni <ITEMNAME>
```


### More to Come!!!

```
tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr > result.txt
```

- tr: transfrom char in first quote into char in second quote
- '<': redirect the file as input file for a command
- sort: rearrange data in ascending order by default
- uniq -c: eliminate duplicates and count the duplicates
- 'n' for numeric and 'r' for reverse order
- '>': redirect output
