## To lower- / uppercase

```bash
echo "AhahA" | awk '{print tolower($0)}' # ahaha
echo "AhahA" | awk '{print toupper($0)}' # AHAHA
```
