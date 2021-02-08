---
title: Execute script -Lutz
published: true
---
Run from system-terminal:
``` dos
>python -m <filename>.py
```
Run from system-terminal and then launch Python-terminal:
``` dos
>python -i filename.py
...
>>>
```
Run from Python-terminal
``` dos
>>>exec(open('filename.py').read())
```

Iteration without reading:
```Python
for line in open('filename.py'):
  print(line)
```
