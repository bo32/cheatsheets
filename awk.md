# AWK

## Simple usage

Print the first column of the input.txt file.

```bash
cat input.txt | awk '{print $1}'          # index starts a 1
# or 
awk '{print $1}' input.txt                # index starts a 1
```

## Extended options

### Specify field separator (or delimiter)

```bash
awk -F ";" '{print $1}' input.txt         # here using ; as a field separator
```


