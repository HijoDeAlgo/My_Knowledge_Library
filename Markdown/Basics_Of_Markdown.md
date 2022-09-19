# **Basics of markdown**

## Preview in *Visual Studio Code* 

To be able to visualize what we are doing at the same time, I can use the visual studio code previewer, pressing **"Ctrl + Shift + P"** or **"F1"** and search for **"Markdown: Preview"** .

#### **Searching for the view**
![Searching_Preview_Markdown](Images_Basics_Of_Markdown\img_Markdown_Preview_Search.png)


#### **Markdown:Preview**
![Markdown:Preview](Images_Basics_Of_Markdown\img_Markdown_Preview.png)





---
# Coments

<!-- This is a comment -->

![Markdown:Preview](Images_Basics_Of_Markdown\img_comment.png)

---
# **Types of headings**


<!-- headings -->
# Heading 1
_Use one #_ then the text.
## Heading 2
_Use two #_ then the text.
### Heading 3
_Use three #_ then the text.
#### Heading 4
_Use four #_ then the text.
##### Heading 5
_Use five #_ then the text.
###### Heading 6
_Use six #_ then the text.

------
----
# Stylizing a text

## Line Breaks

<!-- line breaks -->
<!-- ENTER -->

To break a line, just hit enter.



**Italics**  - just use * or _ at the beginning and after the text you want to use.

<!-- Italics -->
This is an *italic* text

This is an _italic_ text

**Strong**  - just use ** or __ at the beginning and after the text you want to use.

<!-- Strongs -->
This is an **strong** text

This is an __strong__ text

**StrikeTrough**  - just use ~~ at the beginning and after the text you want to use.

<!-- StrikeTrough -->
This is an ~~striketrogh~~ text

---
## Lists
### Unordered lists
<!-- UL -->
* item 1
* item 2
* item 3
    * item 3.1
    * item 3.2    
* item 4

### Ordered lists
<!-- OL -->
1. item 1
1. item 2
1. item 3
1. item 4

---
## Links

Start with square brackets by typing the text you want to appear in the link, then inside () type the URL.

<!-- Links -->
[Google.com](https://www.google.com)

To add an extra tag to it, inside the () you can quote a sub tag that is displayed when you hover over it.

[Google.com](https://www.google.com "Here you write what you want the label to say.")



----
## Quote
<!-- Blockquote -->
Just use > then the text.
> this is a quote

---

## Horizontal Rule
Just type "___" (without the quotes) or "---" (without the quotes).

<!-- Horizontal Rule -->
___
---
## Images

To put images, you must put a symbol !, immediately followed by square brackets [ ] where the name of the element is written, followed by ( ) that contain within them the address in the folder or the URL. Also within the ( ) you can go between quotes "A sub label that will come out when the click is placed on the image".

<!-- IMAGES -->
***Local***


![Vscode Logo](Images_Basics_Of_Markdown\img_java.png  "Imagen local")

**Internet**

![Vscode Logo](https://i.blogs.es/53044d/java/1366_521.jpg "Web Image")

---
# Github MD

<!-- GITHUB MD -->

## Ways to visualize the code

With a ` before the line of code.
<!-- Inline code -->
`console.log('hello world')`

`<h1>Hello world</h1>`

Just use ``` before and after the code to display.

```
first line of code
second line of code
```
And if you want a specific language, you can use ``` followed by the language. Here are some examples:

**```python**

```python
print("hello world")
```

**```javascript**
```javascript
console.log('hello world')

const test = (str) => str + 'test';
```

**```html**
```html
<h1>Hello World</h1>
```

---
## Tables

<!-- TABLES -->
| Product       | Price         |quantity   |
| ------------- |:-------------:| :--------:|
| Laptop        | 3.33          | 2         |
| Mouse         | 10.33         | 1         |

**Wath the characters in this example**

![Tables](Images_Basics_Of_Markdown\img_tables.png  "Tables example")

----
### Task 

To use task, write "* [x] task1"  when it is complete, or * [] task1 when it is incomplete.

* [x] task1
* [] task2
* [] task3
* [x] task4


----
----


## Bibliography (And Mentions) 

<!-- Bibliography (And Mentions) -->
Original first autor: @faztweb :+1: :smile:

[Fazt Code](https://www.youtube.com/watch?v=oxaH9CFpeEE "Youtube Video")

[Faztweb GithubRepo](https://github.com/FaztWeb/markdown-intro "Github Repo")
