# AWK

## Simple usage

Print the second column of the input.txt file.

```bash
cat input.txt | awk '{print $2}'
# or 
awk '{print $2}' input.txt
```

## Extended options

### Specify field separator (or delimiter)

Default delimiter is space character. Can be changed with -F option.

```bash
awk -F ";" '{print $1}' input.txt         # here using ; as a field separator
```


