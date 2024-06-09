# Poetry Reading
### Poetry:
writing that formulates a concentrated awareness of experience in language chosen and arranged to create a specific response

```
with open("poetry.txt") as file:
    line = file.readlines()
    print(line)
    for ix, lineX in enumerate(line):
        line[ix]=lineX.replace('\n','')
    print(line)
```
