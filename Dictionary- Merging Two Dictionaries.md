## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

Add code here
~~~
dict1=eval(input())
dict2=eval(input())
merge={**dict2,**dict1}
print(merge)
~~~

## Output
<img width="1147" height="232" alt="image" src="https://github.com/user-attachments/assets/870c02a9-da0f-4a74-b9a9-8e7c36ae316a" />


## Result
Thus the python program is done.
