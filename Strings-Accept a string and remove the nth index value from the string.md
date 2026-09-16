# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program

```python id="r6k3wp"
def remove(string):
    n = int(input("Enter the index to remove: "))
    a = ""

    for i in range(len(string)):
        if i != n:
            a = a + string[i]

    return a


string = input("Enter a string: ")

result = remove(string)

print("String after removing the character:", result)
```

## Output

```text id="v2n8qm"
Enter a string: Python
Enter the index to remove: 2
String after removing the character: Pyhon
```

## Result

Thus, the Python program successfully removes the character at the specified index from the given string.

