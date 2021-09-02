# Github-Markdown

## Table of Content

- [Introduction](#introduction)
- [Header](#header)
- [List](#list)
  - [Unordered](#unordered)
  - [Ordered](#ordered) 
- [Images](#images)
- [Emphasis](#emphasis)
- [Blockqoutes](#blockqoutes)
- [Backslash Escapes](#backslash--escapes)

### Github Flavored Markdowns

- [Introduction](#introduction)
- [Username@mention](#username@mention)
- [Fenced Code Blocks](#fenced--code--locks)
- [Issue References](#issue--references)
- [Task Lists](#task--list)
- [Tables](#tables)
- [Emoji](#emoji)

### Introduction

**Markdown** is a way to style text on the web. You control the display of the document; formatting words as
bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly,
Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

### Header

```Text
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```
### Lists

#### Unordered

```Text
* Item 1
* Item 2
  *Item 2a
  *Item 2b
```
#### Ordered

```Text
1. Item 1
2. Item 2
3. Item 3
  * Item 3a
  * Item 3b
```

### Images

```Text
![Github Logo](/images/logo.png)Format: ![Alt Text](url)
````

### Emphasis

```Text
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
*You **can** combine them*
```

### Links

```Text
http://github.com - automatic![GitHub](http://github.com)
```

### Blockqoutes

```Text
As Grace Hopper said:

> I’ve always been more interested
> in the future than in the past.
``` 
![Screenshot from 2021-09-02 11-29-04](https://user-images.githubusercontent.com/37219226/131828485-0ee8cf23-b713-44ac-a987-14135da81d3e.png)

### Backslash Escape

Markdown allows you to use backslash escapes to generate literal characters which
would otherwise have special meaning in Markdown’s formatting syntax.

```Text
\*literal asterisks\*
```

Markdown provides backslash escapes for
the following characters:

-------------------------------------
|[\ backslash]  |  [_ underscore] |
|\- minus sign (hyphen)  |  . dot |
|{} curly braces  |  * asterisk |
|[] square brackets  |  () parentheses |
|! exclamation mark  |  \` backtick\ |
|\# hash mark  |  + plus sign |
