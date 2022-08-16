# Counting Alabama

This will teach you how to

- import txt file which is the most commond file in the world.
- How to process the text file by using regex and without using regex

## Might need to use

Google - the most powerful search engine.

If I say you need to use `someFunction` try google it like *"someFunction python document"* or *"someFunction python example"*. And, yes, try to actually read the intruction.

## Tasks

### 1 Check the "Alabama-beach-mouse.txt"

Frist thing before import any data to the project,you need to open the file with notepad or excel or whatever your file format is to check whether the file is actually readable and not a wrong file.

### 2 Import the file into the variable call "data" (which will be a string variable)

Try import the file with `with` and `open` function. No need to use `pandas` or `numpy`.

Now, we have a variable call "data" which is a string.

___

Note that python's variable are dynamic type that is we don't need to initialise the variable type before. For example, in

**Java**

```java
String youName = "Newbie"
Int myGrade = 369
```

**C**

```C
char youName[8] = "Newbies"
int myGrade = 369
```

The problem or the dynamic variable type languages like python is it take time to determine the varible when compling the program. Nevertheless, python is very fast to develope since the language is extreme simple and there are 5 billion packages avialable for you to use.

### 3 Count the number of lines of the data

You need the basic knowledge of string that is who a the program know that it needs to to go to the next line.

Try `print(repr(yourString))`.

Note that "repr" is short for "raw representation" that is it will return the raw string instead of format string.

One might try `print(repr("hello \tWorld! \nHello \tNoobs"))` and compare it with `print("hello \tWorld! \nHello \tNoobs")`

#### After finished the task

Just wanna remind you that the computer read the string in code therefore the are no space, no tab, no next line, no indent.If you want to feel more of it you should try Latex (you can try it on overleaf).

### 4 Count the number of word in the data

Try to use function `.split()` - try `print(data.split())` and explore the results.

Try add an argument in the function such as `split("\n")` or `split(".")` and explore the results

### 5 Count the number of sentences in the data

You need to under stand the structure of english sentence.

What is the easiest way way to check the number of sentences in a text assuming that there are all grammartically correct.

**Hint**: You migh use `split` or `find`

### 6 Count the number of the words "Alabama" in the data

### 7 Replace the words "Alamaba" with "Texas"

You might need to use the `replace` function.

### 8 Count the number of articles in the data

You just need the fundamental english knowledge of what is the 'article' in english

### 9 Count the number of word which contains "e" inside

That is easy just use `for` loop, `if` statement, and `find` function

### 10 find the number of words which has 4-6 letters

You might need to remove space and "." before

### 11 find the number of words which contain "e" or "t"

IT's easy! you can do it!

## What we have learnt

- Open file and import data into the program manually
- Use `split`, `count`, and `replace` function
- Yes you might now finally able to understand how `for` loop in python work
- Also you are mastered `if` statement and boolean condition (and, or)
- For ones who has used `regex`, you are able to use regex now.
- You are now able to work with **list** which is the fundamental element of numpy array and pandas dataframe

Now, let's move to the next project!
