# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

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

