---
permalink: reference.html
layout: base.njk
---
[![BF logo](https://base.finance/images/icons/icon-36.png "Logo")](https://github.com/bndp/beautiful-markup)
[*Home*](/beautiful-markup)
[*Reference*](/beautiful-markup/reference)
[*Components*](/beautiful-markup/components)
[*Demo*](/beautiful-markup)
[*Source code*](/beautiful-markup/source)

---

# Reference guide

#### Minimal (3kb) Material Design CSS library for Markdown.

[GitHub](/)


## 1. Usage

Import in your HTML:

    <link rel="stylesheet" href="https://unpkg.com/bfmd.min.css" />


## 2. Typography

*Markdown Syntax:*

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
Paragraph text in **bold** and *italic*
```
*Result:*

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
Paragraph text in **bold** and *italic*

## 3. Link

*Markdown Syntax:*

```
My favorite personal finance manager is [BASE·finance](https://base.finance).
```

*Result:*

My favorite personal finance manager is [BASE·finance](https://base.finance).


## 4. Image

*Markdown Syntax:*

```
[![BF logo](https://base.finance/images/icons/icon-36.png "Logo")](https://base.finance)

![Tbourida Moroccan folklore fantasy by Houssain tork](https://upload.wikimedia.org/wikipedia/commons/4/4a/Tbourida_Moroccan_folklore_fantasy.jpg)
```

*Result:*

[![BF logo](https://base.finance/images/icons/icon-36.png "Logo")](https://base.finance)

![Tbourida Moroccan folklore fantasy by Houssain tork](https://upload.wikimedia.org/wikipedia/commons/4/4a/Tbourida_Moroccan_folklore_fantasy.jpg)


## 5. List

*Markdown Syntax:*

```
Ordered List
1. First item
2. Second item
3. Third item

Unordered List
- First item
- Second item
- Third item
```

*Result:*

Ordered List
1. First item
2. Second item
3. Third item

Unordered List
- First item
- Second item
- Third item


## 6. Table

*Markdown Syntax:*

```
| Title     | Text  | Number  |
| ---       | ---   | ---:    |
| Header    | Word  | 0.10    |
| Paragraph | Text  | 12.45   |
```

*Result:*

| Title     | Text  | Number  |
| ---       | ---   | ---:    |
| Header    | Word  | 0.10    |
| Paragraph | Text  | 12.45   |


## 7. Blockquote (Basic card)

*Markdown Syntax:*

```
> Souvent, pour s’amuser, les hommes d’équipage  
> Prennent des albatros, vastes oiseaux des mers,  
> Qui suivent, indolents compagnons de voyage,  
> Le navire glissant sur les gouffres amers.
```

*Result:*

> Souvent, pour s’amuser, les hommes d’équipage  
> Prennent des albatros, vastes oiseaux des mers,  
> Qui suivent, indolents compagnons de voyage,  
> Le navire glissant sur les gouffres amers.

## 8. Horizontal Rule

*Markdown Syntax:*

```
---
```

*Result:*

---


## 9. Code

*Markdown Syntax:*

```
    <html>
      <head>
        <title>Test</title>
      </head>
```

*Result:*

    <html>
      <head>
        <title>Test</title>
      </head>
