# String Manipulation

In this chapter we will cover printing, inputs, variables and string manipulation

## String

A string is a group of letters and numbers which cant be used for mathematical uses
###Example

```python
"This is a string"
"120"
```

## Integer

An integer is a number that you can perform maths on and can only be whole/real numbers

### Example

```python
2
54
```

## Float

Like an integer, it is a number that you can preform math on but it has to have a decimal (Warning, very small numbers can make this go wacky)

### Example

```python
20.0
4.2
53.2143
```

## Boolean

A boolean is a true of false statement

### Example

```python
True
False
```

## Variables

Variables are a way of storing a data type such as a string, int, float etc. These are important as in most programs you will want to save some sort of data

### Example

```python
variable = 3.2 #float
variabletwo = 10 #int
variablethree = "Variable" #string
informationabouttheITcourse = False #boolean
```

## Print Function

The print function prints information to the black box known as the terminal, it can print all data types

### Example

```python
print ("hello World")
```

If you want to print a variable, the variable needs to not have quotation marks around it

### Example

```python
scottsvariable = "Hello World"
print (scottsvariable)
```

you can also put variables together by adding using a comma

### Example

```python
variableone = "adding"
varibaletwo = "strings"
print (variableone, variabletwo)

```

or by defining it to a seperate variable

### Example

```python
variableone = "adding"
varibaletwo = "strings"
fullvariable = variableone + variabletewo
print (fullvariable)
```

# Challenge 1

Write a program that

- Asks for the first name and then a surname
- Prints both the first name and then the last name
- Prints them both on the same line
