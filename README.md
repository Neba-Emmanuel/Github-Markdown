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

 \ backslash  
 _ underscore
\- minus sign (hyphen)
. dot
{} curly braces
* asterisk
[] square brackets
() parentheses
! exclamation mark
\` backtick\
\# hash mark
+ plus sign

## Github Flavored Markdown

### Introduction

GitHub.com uses its own version of the Markdown syntax, GFM, that provides an additional set of useful
features, many of which make it easier to work with content on GitHub.com.

### Username@mentions

Typing an @ symbol, followed bya username, will notify that personto come and view the comment.
This is called an “@mention”,because you’re mentioning theindividual. You can also @mention
teams within an organization.

### Fenced Code Blocks

Markdown coverts text with four leading spaces into a code block; with GFM you can
wrap your code with```Text \``\` ```to create a code block without the leading spaces. Add an
optional language identifier and your code will get syntax highlighting.

```Text
\```javascript
function test() {
console.log("look ma’, no spaces");
}
\```
```


### Issue References

Any number that refers to an Issue or Pull Request will be automatically converted into a link.

```Text
github-flavored-markdown#1
defunkt/github-flavored-markdown#1
```

### Task List

```Text
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
```



### Tables

You can create tables by assembling
a list of words and dividing them
with hyphens ```Text - ``` (for the first row),
and then separating each column
with a pipe ```Text | ```:



### Emoji

To see a list of every image that is supported, check out

<a href="https://github.com/ikatyang/emoji-cheat-sheet" alt="emoji-cheat-sheet">Emoji Cheat Sheet</a>  @ikatyang

```Text
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
```
