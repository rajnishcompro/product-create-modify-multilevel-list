# If statement syntax and examples
> - [meta] Code:T1
> - [meta] Learning Objective: LO0
> - [meta] CSTA Standard: CPP.L2-05 
> - [meta] Tag-Type: Text
> - [meta] Tag-Subject: Tutorial, if statements,  conditionals

---
Source:Tutorials Point, http://www.tutorialspoint.com/python/python_if_else.htm


## Python IF...ELIF...ELSE Statements

An **else** statement can be combined with an **if** statement. An **else** statement contains the block of code that executes if the conditional expression in the if statement resolves to 0 or a FALSE value.

The _else_ statement is an optional statement and there could be at most only one **else** statement following **if** .

### Syntax

The syntax of the _if...else_ statement is −

```python
if expression:
   statement(s)
else:
   statement(s)
```

### Flow Diagram

![Python if...else statement](images/00/if_else_statement.jpg)

### Example

```python
[interactive]
#!/usr/bin/python

var1 = 100
if var1:
   print "1 - Got a true expression value"
   print var1
else:
   print "1 - Got a false expression value"
   print var1

var2 = 0
if var2:
   print "2 - Got a true expression value"
   print var2
else:
   print "2 - Got a false expression value"
   print var2

print "Good bye!"
```

When the above code is executed, it produces the following result −

```
1 - Got a true expression value
100
2 - Got a false expression value
0
Good bye!
```

## The _elif_ Statement

The **elif** statement allows you to check multiple expressions for TRUE and execute a block of code as soon as one of the conditions evaluates to TRUE.

Similar to the **else**, the **elif** statement is optional. However, unlike **else**, for which there can be at most one statement, there can be an arbitrary number of **elif** statements following an **if**.

### syntax

```python
if expression1:
   statement(s)
elif expression2:
   statement(s)
elif expression3:
   statement(s)
else:
   statement(s)
```

Core Python does not provide switch or case statements as in other languages, but we can use if..elif...statements to simulate switch case as follows −

### Example

```python
[interactive]
#!/usr/bin/python

var = 100
if var == 200:
   print "1 - Got a true expression value"
   print var
elif var == 150:
   print "2 - Got a true expression value"
   print var
elif var == 100:
   print "3 - Got a true expression value"
   print var
else:
   print "4 - Got a false expression value"
   print var

print "Good bye!"
```

When the above code is executed, it produces the following result −

```
3 - Got a true expression value
100
Good bye!
```
