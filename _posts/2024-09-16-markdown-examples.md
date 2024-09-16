---
title:  "Markdown examples"
layout: post
---

# Data is the new gold

## Data can provide insight

### Shaping your data in a proper Star Schema allows he semantic model to harness the power of AI

#### Heading Four (h4)

##### Heading Five (h5)

###### Heading Six (h6)

# Heading One will include line

## Heading One will also include line

### Single line

> My mom always said life was like a box of chocolates. You never know what you're gonna get.

### Multiline

> Be sure that your fact tables reference your 
dimension tableswith primary ket from the dimesion table.  The surrogate key should be an integer data type.
>
> Fact tables are shaped long and thin, while the dimension tables tend to be shaped wide and short.
>
> – _Hal Incandenza_

## To add an additional line to a Heading 1 or 2 use 3 dashes ---

---
---

## To create a TABLE use the | symbol to separate coloumn names

| Title 1          | Title 2          | Title 3         | Title 4         |
|------------------|------------------|-----------------|-----------------|
| First entry      | Second entry     | Third entry     | Fourth entry    |
| Fifth entry      | Sixth entry      | Seventh entry   | Eight entry     |
| Ninth entry      | Tenth entry      | Eleventh entry  | Twelfth entry   |
| Thirteenth entry | Fourteenth entry | Fifteenth entry | Sixteenth entry |

## Code

Source code can be included by fencing the code with three backticks ```. Syntax highlighting works automatically when specifying the language after the backticks.

````
```python
import pandas as pd
df = pd.read_csv('data/sample.csv')
df.head()
```
````

This would be rendered as:

```python
import pandas as pd
df = pd.read_csv('data/sammple.csv')
df.head()
```

## Lists

### Unordered

* First item
* Second item
* Third item
    * First nested item
    * Second nested item

### Ordered

1. First item
2. Second item
3. Third item
    1. First nested item
    2. Second nested item
