# `22` Integral

With a given integral number n, write a program to generate a dictionary that contains (i, i*i) such that is an integral number between 1 and n (both included). Then the program should print the dictionary.

## 📝 Instructions:

1. Create a function called `generate_dict`.
2. The function should return a dictionary with the number of keys passed by parameter (starting from one).

## Example input:

```py
generate_dict(8)
```
## Example output:

```py
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}
```

## 💡 Hints:
In case of input data being supplied to the question, it should be assumed to be a console input.
Consider use dict()