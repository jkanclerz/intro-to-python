# Instalacja pythona w systemie

cmd lub powershell lub terminal
```
python
```

interaktywna konsola

```
Python 3.7.4 (default, Oct 12 2019, 18:55:28) 
[Clang 11.0.0 (clang-1100.0.33.8)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> print('hello')
hello
>>> exit
Use exit() or Ctrl-D (i.e. EOF) to exit
>>>
```


plik skryptu hellp.py

```python
import sys

# Define a main() function that prints a little greeting.
def main():
  if len(sys.argv) >= 2:
    name = sys.argv[1]
  else:
    name = 'World'
  print 'Hello', name

# This is the standard boilerplate that calls the main() function.
if __name__ == '__main__':
  main()
```

```
python hello.py
```