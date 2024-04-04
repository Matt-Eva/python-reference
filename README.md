# Python Reference

This repository serves as a reference for different pieces of python functionality.

Each folder corresponds to an individual pieces of python functionality - for example, how to iterate through a dictionary in python - and contains a single file with code examples and (possibly) a README describing how to use the code.

Each example code example will also be listed in this README. Use `Ctrl + f` or `Cmnd + f` to quickly lookup which piece of functionality you're looking for

## dictionary iteration.

```
my_dict = {"key": "value"}

for key in my_dict:
    print("printing key", key)
    print("printing value", my_dict.get(key))
```

# the not operator

```
if not False:
    print("this will print")

if not True:
    print("this will not print")
```
