## Longest Substring Without Repeating Characters

Write a Python function that finds the length of the longest substring without repeating characters in a given string. For this exercise, a substring is a contiguous block of characters within a string.

### Input Description:

- A single string `s`.

### Output Description:

Return an integer representing the length of the longest substring of `s` that contains no repeating characters.

### Sample Solution:

```python
def length_of_longest_substring(s):
    # replace pass with your implementation
    pass

if __name__ == '__main__':
    s = "abcabcbb"
    print(length_of_longest_substring("abcabcbb"))  # "abc"
    print(length_of_longest_substring("bbbbb"))     # "b"
    print(length_of_longest_substring("pwwkew"))    # "wke"
    print(length_of_longest_substring(""))          # ""
    print(length_of_longest_substring(" "))         # " "
    print(length_of_longest_substring("au"))        # "au"
    print(length_of_longest_substring("dvdf"))      # "vdf"

```