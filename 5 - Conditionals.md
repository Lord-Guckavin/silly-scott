TITLE: Conditions 

In this chapter we will cover the grand world of getting your 
code to actually do something. We will start will the humble `if` 
statement. It takes a varible and compares it to something else 
geting a return value.

```python
name == input("What's your name?")

if name == "Mc Cully":
    print("Yo yo it's MC Scottolot")
elif name == "Mr dingus":
    print("Dingaling Ding Donk")
else:
    print(f"Hello {name}")
```

Above is the extent of `if` statements. `if name == "Mc Cully"` checks 
if the name entered is "Mc Cully" and if thats the case it does the 
indented code which is `print("Yo yo it's MC Scottolot")` then skips 
over the `elif` and `else` statements. If the name wasn't `Mc Cully`
then 

