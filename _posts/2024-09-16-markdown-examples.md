---
title:  "Markdown examples"
layout: post
---

# Data is the new gold - Heading #1 contains largest font size

## Data can provide insight - Heading #2 font size decreases with each additional #

### Shaping your data in a proper Star Schema allows he semantic model to harness the power of AI - Heading #3 contains 3# (###)

#### Heading Four - contains 4 hashtags (####)

##### Heading Five - contains 5 hashtags (#####)

###### Heading Six - contains 6 hashtags (######)

Using 7 hashtags (#######) has not affect

# Heading One will include line

## Heading One will also include line

### Single line

> My mom always said life was like a box of chocolates. You never know what you're gonna get.

### Multiline

> Be sure that your fact tables reference your 
dimension tables assigned surrogate key from the dimesion table.  The surrogate key should be an integer data type.
>
> Fact tables are shaped long (many rows)  and thin (few columns), while the dimension tables tend to be shaped short(fewer rows) and wide (more columns)

The underscore symbol _ and the Asteric symbol * are both used to bold and italics.  Use 1 symbol for italics, use 2 symbols for bold.
>
>_Use one underscore directly before and after to display text in italics_

*Use one asterics directly before and after to display text in italics*

To display in bold use double asterics ** before and after words with no spaces from start of bold and no spaces from the end of the bold
**bold and bold**

For both bold and italics use 3 symbols of either * or _

***Bold and Italics***

Use double tilde ~ sign to cross off

~~crossed off~~

Use double equal sign = to highlight, this will not work in Github markdown, so try the before and after to highlight.

Can use html for extended markdown features for github markdown.

<mark>highlight a line or words</mark>  be sure to use the / to end your highlighting.

This is a ^superscript^ that is not not supported in Github markdown.

So use HTML tags for this feature: using "x< sup>2</ sup> + y< sup>2</ sup>" without space

x<sup>2</sup> + y<sup>2</sup>

This is a ~subscript~ that is not not supported in Github markdown.

So use HTML tags for this feature: using H< sub>2</ sub>O without spaces

H<sub>2</sub>O

To add a line use 3 dashes ---

---

## To create a TABLE use the | pipe symbol to separate column names, followed by the Pipe and dashes to determine the colmn isze for each column |----------|

| Title 1          | Title 2          | Title 3         | Title 4         |
|-----------------|--------------------|-----------------|-----------------|
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

You can aso 

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




| Title 1          | Title 2          | Title 3         | Title 4         |            |-----------------|