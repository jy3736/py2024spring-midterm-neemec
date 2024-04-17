## Determine the Index of the Second Largest Number in a List

Develop a program that calculates the position of the second largest integer within a list of numbers. Consider that the list may include duplicates of any number, including the largest and second largest values. Ensure your program appropriately handles these scenarios.

### Python Solution (`main.py`)

```python
def find_index_2nd_max(sequence):
    # replace pass with your implementation
    pass

if __name__ == "__main__":
    test1 = [9, 8, 7, 6, 5, 4, 3, 2, 1, 0]              
    print(find_index_2nd_max(test1))                      
    test2 = [5, 5, 5, 5, 5, 6, 5, 7, 5, 5]
    print(find_index_2nd_max(test2))                    
    test3 = [10, 20, 30, 40, 50, 40, 30, 20, 10, 0]
    print(find_index_2nd_max(test3))
    test4 = [1,1,7,7,2,8,8,8,2,3,3,4,4,5,5,6,6,7,7,7,7]
    print(find_index_2nd_max(test4))

# Output:
# 1
# 5
# 3
# 2
```