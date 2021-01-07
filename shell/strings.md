# Strings

## To lower- / uppercase

```bash
echo "AhahA" | awk '{print tolower($0)}' # ahaha
echo "AhahA" | awk '{print toupper($0)}' # AHAHA
```

## substring

```bash
INPUT="TestWithStrings"
echo ${INPUT:4:2}   # Wi
echo ${INPUT:4}     # WithStrings
```

## length

```bash
echo -n "1234567890" | wc -c     # 10     the '-n' option ignores the eod of line character
```
