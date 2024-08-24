[![MSM Logo](https://github.com/davidwhitemsm/images-for-readme-documentation/blob/main/v4%20MSM%20Logo_URL_Tagline-01.png)](https://msmdesign.nyc/)

# Markdown Cookbook  

**Compiled by David White <david@msmdesign.nyc>**

**Adapted from [*The Markdown Guide*](https://www.markdownguide.org/book) by Matt Cone**  

***

## 01. Headings & Paragraphs

```markdown
<!-- heading syntax -->

# Heading 1  
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 
```

***
`heading examples`

# Heading 1  

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6  

***

## 02. Emphasis

```markdown
<!-- emphasis syntax -->

**bold**

*italic*

***bold and italic***

~~strikethourgh~~
```

***
`emphasis examples`

**bold**

*italic*

***bold and italic***

~~strikethourgh~~
***

## 03. Line Breaks  

```markdown
<!-- line break syntax -->

To create a line break, add two blank spaces at the end of a line and then press `RETURN`.  
```

`line break example`  

This is line 1.  
This is line 2.

***

## 04. Horizontal Rules

```markdown
<!-- horizontal rule syntax -->

***
```

`horizontal rule example`
***

## 05. Block Quotes

```markdown
<!-- block quote syntax -->


> single-line block quote  

‎  

> multi-line
> block
> quote   

‎


> multi-line
> block  
> quote with
>
> space    

‎

> multi-line
> block
> quote with
>> nested text within
>>
> the larger block quote
```

***

`block quote examples`

> single-line block quote  

‎

> multi-line  
> block  
> quote  

‎
> multi-line  
> block  
> quote with  
>
> space  

‎

> multi-line
> block
> quote with
>> nested text within
>>
> the larger block quote

***

## 06. Code Blocks

### Inline Code

```markdown
<!-- inline code syntax -->
enclose `code` in backticks
```

`inline code example`

enclose `code` in backticks

### Code Fences

```markdown
<!-- code fence syntax -->
 - three backticks (```) followed by the name of the programming language
 - your code snippet
 - three backticks

<!-- If the word or phrase you want to denote as code includes backticks,  
escape it by enclosing the entire line in double backticks

For example:
``Use `code` in your markdown file.`` -->
```

`code fence example`

```sql
SELECT *
FROM table1
LEFT JOIN table2
ON id.table1 = id.table2
WHERE state = NY
LIMIT 1000
```

***

## 07. Lists

### Ordered Lists

```markdown
<!-- ordered list syntax -->
1. first item
1. second item
1. third item
    1. indented item 1
    1. indented item 2
1. fourth item
```

`ordered list example`

1. first item
1. second item
1. third item
    1. indented item 1
    1. indented item 2
1. fourth item

### Unordered Lists

```markdown
<!-- unordered list syntax -->
- first item
- second item
- third item
    - indented item 1
    - indented item 2
        - double-indented item 1
        - double-indented item 2
- fourth item
<!-- if you need to start an unordered list item with a number followed by a period,  
you can use backslash (\) to escape the period -->
```

`unordered list example`

- first item
- second item
- third item
    - indented item 1
    - indented item 2
        - double-indented item 1
        - double-indented item 2
- fourth item

### Checklists

```markdown
<!-- checklist syntax -->

- [x] ballot box with check
- [x] ballot box with check
- [ ] ballot box without check
```

`checklist example`

- [x] ballot box with check
- [x] ballot box with check
- [ ] ballot box without check

***

## 08. Tables

```markdown
<!-- table syntax -->

<!-- the row directly below the column header determines the column's text alignment -->

| Column A Header (left justified text) | Column B Header (centered text) | Column C Header (right justified text) |
| :---               | :----:             | ---:               |
| Table Data Cell A1 | Table Data Cell B1 | Table Data Cell C1 |
| Table Data Cell A2 | Table Data Cell B2 | Table Data Cell C2 |
| Table Data Cell A3 | Table Data Cell B3 | Table Data Cell C3 |
| Table Data Cell A4 | Table Data Cell B4 | Table Data Cell C4 |
| Table Data Cell A5 | Table Data Cell B5 | Table Data Cell C5 |
```

`table example`

| Column A Header (left justified text) | Column B Header (centered text) | Column C Header (right justified text) |
| :---               | :----:             | ---:               |
| Table Data Cell A1 | Table Data Cell B1 | Table Data Cell C1 |
| Table Data Cell A2 | Table Data Cell B2 | Table Data Cell C2 |
| Table Data Cell A3 | Table Data Cell B3 | Table Data Cell C3 |
| Table Data Cell A4 | Table Data Cell B4 | Table Data Cell C4 |
| Table Data Cell A5 | Table Data Cell B5 | Table Data Cell C5 |

***

## 09. Links

```markdown
<!-- link syntax -->  
  
method 1:  
[LINK TEXT](URL "title rendered as tooltip")

method 2:    
enclose URL or email address in angle brackets <email@domain.com>
```

`method 1 link example`  
[The Huffington Post](https://www.huffpost.com/ "HuffPost - Breaking News, U.S. and World News | HuffPost")

`method 2 link example`  
<arianna@huffingtonpost.com>
***

## 10. Images

### Unlinked Images

```markdown
<!-- unlinked images syntax -->  

![alt text](file_path_or_URL "image title")  
```

`unlinked image example`  

![Markdown Logo](https://github.com/dcurtis/markdown-mark/blob/983259b19bbc9673e9cf337b98ac899bf8a1484a/png/208x128.png "Markdown Logo 208x128.png")

### Linked Images

```markdown
<!-- linked images syntax-->  

To add a link to an image, enclose the Markdown for the image in brackets,  
and append the link URL enclosed in parentheses.  
[![alt text](file_path_or_URL "image title")](image_URL)
```  

`linked image example`  

[![Markdown Logo](https://github.com/dcurtis/markdown-mark/blob/983259b19bbc9673e9cf337b98ac899bf8a1484a/png/208x128.png "visit: https://en.wikipedia.org/wiki/Markdown")](https://en.wikipedia.org/wiki/Markdown)

***

## 11. Footnotes  

```markdown

<!-- footnotes syntax -->  

This is a short footnote[^1] and this is a longer footnote [^2] followed by some additional text.

[^1]: A single-line reference.
[^2]: A multi-line reference.
        Indent parageaphs to include them in the footnote.  
        Use back ticks to include `code`.  
        Your reference may be as many lines long as you'd like.
```

`footnotes example`

This is a short footnote[^1] and this is a longer footnote [^2] followed by some additional text.

[^1]: A single-line reference.
[^2]: A multi-line reference.
        Indent parageaphs to include them in the footnote.  
        Use back ticks to include `code`.  
        Your reference may be as many lines long as you'd like.

***  
