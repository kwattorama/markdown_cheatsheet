# Markdown Cheatsheet

## What is Markdown and Markdown syntax

* Markdown is **[markup](https://www.techopedia.com/definition/2668/markup-language)** language like [LaTex](https://www.latex-project.org/) and [HTML](https://en.wikipedia.org/wiki/HTML)
* Filename extension is **.md**
* Markdown files are just formatted text files
* Markdown syntax is plain text formatting syntax
* Use writing up web content faster - texts links and embed code or images in texts
* Markdown is great for **README**'s, messages in forums and for documentation
* Main purpose of Markdown is **Readability** and **Ease of use**.

---

## Headings

**Syntax:** Use pound sign/hash `#` symbol.
**Note:** Add space after `#`.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

# Heading 1
## Heading 2
### Heading 3
#### Heading 4

---

## Paragraph

**Syntax:** Use one blank line for seperation of paragraphs. To break the line press `Enter` key after trailing two white spaces or type `<br>`

```markdown
Python is an interpreted, high-level, general-purpose programming language.
<!-- blank line left to start new paragraph -->
My presence is a gift.<br>Fun is where I am.<br>I make things happen. Smoothly
```

Python is an interpreted, high-level, general-purpose programming language.
<!-- blank line left to start new paragraph -->
My presence is a gift.<br>Fun is where I am.<br>I make things happen. Smoothly

---

## Formatting

### Bold

**Syntax:** Use double asterisks or underscores.

```markdown
I am **bold** by asterisk. I am __bold__ by an underscore.
```

I am **bold** by asterisk. I am __bold__ by an underscore.

### Italic

**Syntax:** Use single asterisk or underscore.

```markdown
I am *italic* by asterisk.<br>I am _italic_ by undrescore.
```

I am *italic* by asterisk.
I am _italic_ by undrescore.

### Bold and Italic

**Syntax:** Use triple asterisk.

```markdown
I am ***italic and bold*** by triple asterisk.
```

I am ***italic and bold*** by triple asterisk.

### Strikethrough

**Syntax:** Use double tidle(~) symbol which is below Esc Key.

```markdown
I'm ~~good~~ great!
```

I'm ~~good~~ great!

---

## Blockquotes

**Syntax:** Use greater than`>` symbol at the start of every line. For nested blockquotes use `>>`.

```markdown
> asato mā sadgamaya  
> tamasomā jyotir gamaya  
> mrityormāamritam gamaya
>> Oṁ śhānti śhānti śhāntiḥ
```

> asato mā sadgamaya  
> tamasomā jyotir gamaya  
> mrityormāamritam gamaya
>> Oṁ śhānti śhānti śhāntiḥ

---

## Links

### Hyperlinks

**Syntax:** [text to link](http:link here)

```markdown
Python is [general-purpose programming language](https://en.wikipedia.org/wiki/General-purpose_programming_language)*.
```

Python is [general-purpose programming language](https://en.wikipedia.org/wiki/General-purpose_programming_language).

### Images

**Syntax:** ![keep blank or ImageName or AltText](both local and web URL are supported)

```markdown
![ ](http://browserengine.net/wp-content/uploads/1441861327mdh-logo-new.png)
```

![ ](http://browserengine.net/wp-content/uploads/1441861327mdh-logo-new.png)

---

## Lists

### Unordered List

**Syntax:** Use hypen `-` or plus `+` or an asterisk `*` and write the sublist with indentation.

```markdown
* Unit 1
- Unit 2
  - Unit 2.1
  - Unit 2.2
      - Unit 2.2.1
+ Unit 3
```

* Unit 1
- Unit 2
  - Unit 2.1
  - Unit 2.2
      - Unit 2.2.1
+ Unit 3

### Ordered List

**Syntax:** Use number dot or period `.` and write the sublist with indentation.

```markdown
1. Topic 1
	1. SubTopic
2. Topic 2
3. Topic 3
4. Topic 4
```

1. Topic 1
	1. SubTopic
1. Topic 2
1. Topic 3
1. Topic 4

### Task List

```markdown
- [x] Completed task name
- [ ] Unfinished task name
```

- [x] Completed task name
- [ ] Unfinished task name

---

## Code

### In-line Code

**Syntax:**

```markdown
`This is inline code`
```

`This is inline code`  

### Block of Code

**Syntax:** Name of the programming language followed by enclosed triple Grave accents or back ticks (**```**).

` ```languageName`
` ``` `

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

` ```javascript `
let num = Math.square(10)
` ``` `

```javascript
let num = Math.square(10)
```

## Table

**Syntax:** Made by using pipe `|` which is above `Enter` key. First two rows with pipe `|` and minus `-` symbol are use to make header and new column.

```markdown
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

---

## Comment

**Syntax:**

```markdown
<!-- comment written in markdown -->
```

---

## Horizontal Line

**Syntax:** Three or more than three hyphens `-` or asterisks `*` or underscores `_`.

```markdown
___
***
---
```

___
***
---

---

Feel free to improve this cheatsheet. To see Markdown syntax used to make this readme file click [here](https://raw.githubusercontent.com/kwattorama/markdown_cheatsheet/master/README.md).
