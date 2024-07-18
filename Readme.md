# Quick guide how to write Markdown
---

## Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Paragraph
Normal text. Not symbol use

## Codes
Use three backticks pair `````` and write code inside it.

```JavaScript

let name = "Coder";
console.log(name);
```

## List

**Ordered List**

```
1. One
2. Two
3. Three
```

**Unordered List**

```
- One
- Two
- Three
```

## Links

`[Name you want to give](Link of website)`

**Ex:** `[React](https://react.dev)`


## Images

`![Alt text](Image link)`


## Tables

```
| Name | Desc |
| --- | --- |
| Bishal | Coder |
```

---
***
---

### Detailed part starts from here

# To write heading in Markdown

**_We can only use 6 headings as stated below:_**

---
---

**Syntax :** `# Heading 1` 
# Heading 1
---

**Syntax :** `## Heading 2` 
## Heading 2
---

**Syntax :** `### Heading 3` 
### Heading 3
---

**Syntax :** `#### Heading 4` 
#### Heading 4
---

**Syntax :** `##### Heading 5` 
##### Heading 5
---

**Syntax :** `###### Heading 6` 
###### Heading 6

***


# To write paragraph in Markdown
---
---

We just simply write it.

*** 

# To make text bold, italic, strike and underline
---
---

## Bold
**Syntax:** `**Text**`
**Output:** **Text**

---

## Italic
**Syntax:** `_Text_`
**Output:** _Text_

---

## Strike Through
**Syntax:** `~~Text~~`
**Output:** ~~Text~~

---

## Underline
**Syntax:** `<u>Text</u>`
**Output:** <u>Text</u>

Generally underline does not visible clearly so better to make **bold** than <u>underline</u>.

---

# To make List
---
---

### Ordered List

**Syntax:** `1. List item`
Use numbers normally as we make list

1. React
2. JavaScript
3. Nodejs

---

### Unordered List

**Syntax:** `- List item`
Use "- " dash sign and space to make unodered list 

- React
- Tailwind
- Full Stack

---

# To add links

---
---

### Links

**Syntax:** `[Name you want to display](website link)`

**Example:** `[React](https://react.dev/)`

**Output:** [React](https://react.dev/)

---

### To display text when we hover on link:

**Syntax:** `[Name you want to display](website link "Text you want to display when hover")`

**Example:** `[React](https://react.dev/ "Text to display")`

**Output:** [React](https://react.dev/ "This is react site")

---

# To add image

---
---

## Image

**Syntax:** `![Alt text](image link or file path)`

**Example:** `![React](https://cdn.iconscout.com/icon/free/png-512/free-react-1-282599.png?f=webp&w=256)`

**Output:**
 ![React Image](https://cdn.iconscout.com/icon/free/png-512/free-react-1-282599.png?f=webp&w=256)

---

## Display text when hover on image

Same as link

**Syntax:** `![Alt text](image link or directory path "Text to display")`

**Example:** `![React](https://cdn.iconscout.com/icon/free/png-512/free-react-1-282599.png?f=webp&w=256 "React image")`

**Output:**
 ![React Image](https://cdn.iconscout.com/icon/free/png-512/free-react-1-282599.png?f=webp&w=256 "React Image is displaying")

---

# To add quotes
---
---

**Syntax:** `> Coding is fun`

**Output:** 
> Coding is fun

---

# To add code
---
---

### To add single line of code:
 use backtick `` and write code inside backtick.

 Ex: `npm run dev`

 ---

### To add multiple line of code

use three backticks pairs `````` and add code inside it. You can give programming language name at start as it highlights the code accordingly.

Ex: 
```JavaScript
let name = "JavaScript";
console.log(name);
```

```Python
name = "Python"
print(name);
```

---

# To add horizontal line
---
---

**You can either use --- and *** , both are same**

**Syntax:** `---` or `***`

---

# To create table
---
---

**Syntax:** 

```
| Heading | Description |
| --- | --- |
| Code | Best thing |
```

**Output:**
| Heading | Description |
| --- | --- |
| Code | Best thing |

***

# To make checkbox

---
---

**Syntax for checked box:** `- [x] Checked`

**Output:** 
- [x] Checked

---

**Syntax for unchecked box:** `- [ ] Checked`

**Output:** 
- [ ] Unchecked

***

#### NOTE
Sometimes when you write md code, in some cases your code won't work on your system but it will work on Github. So to make your code work on your system same as Github then you have to install some extension to make it possible. I use extension named **[Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)** but you can choose any extension you like.

**Do not just read the Readme.md preview but read Readme.me file and it's preview simultaneously for better understanding.**

---

**Congratulation👍🎉 You have learnt how to make Markdown.**
**This is Bishal, signing off.**