# Markdown Cheatsheet
## What is Markdown and Markdown syntax?
* Markdown is [markup language](https://www.techopedia.com/definition/2668/markup-language) like LaTex and HTML
* Filename extension>>  **.md**
* Markdown files are just formatted text files.
* markdown syntax: plain text formatting syntax
* writing up web content faster - texts links and embed code or images in texts 
* **Markdown is great for readme's**, messages in forums and for documentation
* Main purpose: Readability and easy to use.
----

**Headings:** use pound sign/hash symbol. Keep space after '#' 

```Markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
-----------------------------------------------------

**Bold text**: use double asterisk or underscore.
```Markdown
I am **bold** by asterisk. I am __bold__ by undrescore.
```

I am **bold** by asterisk.
I am __bold__ by undrescore.

-----------------------------------------------------

**Italic text**: use single asterisk or underscore.

```Markdown
I am *italic* by asterisk. I am _italic_ by undrescore.

```
I am *italic* by asterisk.
I am _italic_ by undrescore.

-------------------------------------------------------
**Bold and Italic text**: use triple asterisk
```Markdown
I am ***italic and bold*** by asterisk.
```

I am ***italic and bold*** by asterisk.

---------
**Blockquotes:** add > symbol in front of a paragraph. for nested blockquotes use >>

```Markdown
> asato mā sadgamaya
>
>tamasomā jyotir gamaya 
>
>mrityormāamritam gamaya 
>
>>Oṁ śhānti śhānti śhāntiḥ
```

> asato mā sadgamaya
>
>tamasomā jyotir gamaya 
>
>mrityormāamritam gamaya 
>
>>Oṁ śhānti śhānti śhāntih
------

**Straightthrough:** : use double Tidle(~) symbol which is below Esc Key  

```Markdown
~~Straightthrough~~
```

~~Straightthrough~~

----------------------------------------------------
**Paragraph:** 




**Unordered List**: use hypen(-) or plus(+) or asterick(*) and write the sublist with indentation(2 spaces)

```Markdown
* Unit 1          
- Unit 2
  - Unit 2.1
  - Unit 2.2
+ Item 3
```

* Unit 1          
- Unit 2
  - Unit 2.1
  - Unit 2.2
+ Unit 3

---------------------------------------------------
**Ordered List**: use number dot(1.) and write the sublist with indentation

```Markdown
1. Item1
1. Item2
1. Item3
1. Item4
```

1. Topic 1
	1. Sub Topic
1. Topic 2
1. Topic 3
1. Topic 4
-----------------------------
**Block code for a particular language:**use Grave accent ( ` ), Below Esc key

` ```languageName`
  
  ` ``` `


example1: 

` ```python`

a = 3

b = 7

print(f"Addition of {a} and {b} is {a + b}")
  
` ``` `

```python
a = 3
b = 7
print(f"Addition of {a} and {b} is {a + b}")
```

example2: 

` ```javascript `

let num = Math.square(10)

` ``` `
```javascript
let num = Math.square(10)
```
------------------------------------------------------
**Table:** made by using pipe( | ) which is above `Enter` key. 
- First two rows with pipe(|) and minus(-) symbol are use to make header and new column


```Markdown
| Vitamin |Source| Deficiency diseases |
| ---| --- | --- |
| A | Carrot  |Night blindness|
| D | Sunlight| Rickets| 
| C | Lemon| Scurvy|
|K| Green vegetable|Beri-Beri
```

| Vitamin |Source| Deficiency diseases
| ---| --- | --- 
| A | Carrot |Night blindness
| D | Sunlight| Rickets
| C | Lemon| Scurvy
|K| Green vegetable|Beri-Beri
