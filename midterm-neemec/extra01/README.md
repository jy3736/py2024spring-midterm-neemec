## Rotate String

Write a Python function that rotates a string to the right by a given number of positions. If the number of positions is greater than the string length, the rotation should continue from the beginning. This means the function should rotate the string as many times as the number of positions specified, wrapping around to the start of the string as needed.

### Input Description:

- A string `s` that needs to be rotated.
- An integer `n` specifying the number of positions to rotate the string to the right.

### Output Description:

Return the rotated string.

### Sample Solution:

```python
def rotate_string(s, n):
    # replace pass with your implementation
    pass

if __name__ == '__main__':
    s = "hello"
    print(rotate_string(s, 1)) # "ohell"
    print(rotate_string(s, 2)) # "lohel" 
    print(rotate_string(s, 3)) # "llohe"
    print(rotate_string(s, 4)) # "elloh"
    print(rotate_string(s, 5)) # "hello"
    print(rotate_string(s, 6)) # "ohell"

```