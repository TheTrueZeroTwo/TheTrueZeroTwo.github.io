# Blog template

# Markdown syntax and examples
## Contents
[//]: # '### * [Headings](https://github.com/KazMalhotra/blog#heading-1)'
[//]: # '### * [Text styling](https://kazmal.tech/blog#text-styling)'
[//]: # '### * [Block Quotes](https://kazmal.tech/blog#block-quotes)'
[//]: # '### * [Superscript and Subscript](https://kazmal.tech/blog#superscript-and-subscript)'
[//]: # '### * [Code blocks](https://kazmal.tech/blog#code-blocks)'
[//]: # '### * [Tables](https://github.com/kazmalhotra/blog#tables)'
[//]: # '### * [Lists](https://kazmal.tech/blog#lists)'
[//]: # '### * [Links](https://kazmal.tech/blog#links)'
[//]: # '### * [Strikethrough](https://kazmal.tech/blog#strikethrough)'
###  [Go to a blog post](posts/1.html)
###  [testing md post](posts/1.md)

# Heading 1
## Heading 2  
### Heading 3  
#### Heading 4
##### Heading 5
###### Heading 6    


### Text styling
#### Renders as
\*ignore markdown characters\*  
*Italic*  
**Bold**  
**_Bold and italic_**  
#### Source
```
\*ignore markdown characters\*  
*Italic*  
**Bold**  
**_Bold and italic_**  
```
### Block quotes
#### Renders as
> Intelligence is the ability to avoid doing work, yet getting the work done.    
> -Linus Torvalds
#### Source 
```
> Intelligence is the ability to avoid doing work, yet getting the work done.    
> -Linus Torvalds
```

### Superscript and subscript
#### Renders as
##### Superscript demonstrated by Einstein's famous Mass–energy equivalence
E=MC<sup>2</sup>  
##### Subscript demonstrated by the equation for finding the Nth Fibonacci number recursively
F<sub>n</sub>=F<sub>n-1</sub>+F<sub>n-2</sub>
#### Source
```
##### Superscript demonstrated by Einstein famous Mass–energy equivalence
E=MC<sup>2</sup>  
##### Subscript demonstrated by the equation for finding the Nth Fibonacci number recursively
F<sub>n</sub>=F<sub>n-1</sub>+F<sub>n-2</sub>
```
### Code blocks
`Wow, code block`
```
Multi-line code block  
In markdown, makes a haiku
Japanese poem
```    
With JS syntax highlighting
``` js
function fib(n){
  if(n < 2) return n;
  return fib(n - 1) + fib(n - 2);
}
```

### Tables
#### Renders as
| Column | Different column |
| ------ | ----------- |
| Table thing one  |*they're called arguments* |
| Row | **No, they're called parameters** |
| Cell| `Actually, they're called cells.` |
#### Source
```
| Column | Different column |
| ------ | ----------- |
| Table thing one  |*they're called arguments* |
| Row | **No, they're called parameters** |
| Cell| `Actually, they're called cells.` |
```
### Lists
#### Renders as
* Top list       
    *-Other thing*
* Top list 2 
    1. *Foo*
    2. *Bar*
    3. *Ack*


1. List item 
2. *List item*  
3. **_List item_**

- List item 1  
- List item 2  
- List item 3  

#### Source
```
* Top list       
    *-Other thing*
* Top list 2 
    1. *Foo*
    2. *Bar*
    3. *Ack*


1. List item 
2. *List item*  
3. **_List item_**

- List item 1  
- List item 2  
- List item 3  
```

### Strikethrough
#### Renders as
~~the earth is flat~~
#### Source
```
~~the earth is flat~~
```
