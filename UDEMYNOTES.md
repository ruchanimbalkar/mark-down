# More about Markdown

I took a course on Udemy and these are my notes :

## Background

 Markdown syntax was first proposed by John Gruber in 2004.

---

## Use cases for Markdown

- Cloud based note-taking.
- Outlining or brain-storming.
- Composition
- Pros or scripts for a play.
- Content for a blog or website.
    - Example : [Charmed](https://popcorn.forem.com/ru_3fe1be0fc49561bfb3b6c8/charmed-tv-show-251m)


---
## Online Markdown Editors

- [StackEdit](https://stackedit.io/)
- [Online MarkDown](https://onlinemarkdown.com/)


---

## How to separate paragraphs?

To separate paragraphs, hit return/enter twice.

This is my second paragraph.

---

## Hot to add line break?

To add line break, add two spaces  at the end of the line  .

**Example** : 
I ate some candy then I went to the mall.  I bought a doll. I forgot it is fall.  
I had a shopping haul.
---

## How to have underscore around a variable name in markdown?

Use backslash before the underscore

 This is **bold** text. This is *italic* text. This is a variable name monthly\_salary_.

 **Examples** :

 - favorite\_song  
-  num\_of\_guests

---
## Blockquote Example

> Always remember you are absolutely unique  just like everyone else.
### _Margaret Mead_

---

## How to write code examples ?

### Inline syntax: Use back ticks.

The `rm` command is used to delete files in bash.

### Block syntax: Indent by four spaces
            ~rm
            ls ~l
            rm myfile.txt
            # this is a comment
            var test = `test`

Note : Within a code block, the back tick is ignored.

---

## How to write an unordered list?

Use -, * or  +.

- Apple
+ Orange
* Mango

Note: Be consistent with whichever thing you use.

**Example: How to write a nested unordered list**:
- Fruits
    - Guava
    - Chikoo
    - Peach
- Vegetables
    - Potato
    - Cauliflower
    - Cabbage


---

## How to write a nested ordered list ?

Use numbers and creat a new list after the list item.

    
**Example** :
1. SearchEngines
    1. Google
    2. Bing
    3. YouTube
2. Browsers
    1. Chrome
    2. Bing
    3. Duck Duck Go


Note: You can incorporate paragraphs, quotes or codeblocks in your list.

    
**Example** :
1. Programming Languages
    1. Python
    ```Python
        print("Hello, world!")
    ```
    2. JavaScript
    ``` JavaScript
        console.log("This is JavaScript");
    ```
    3. SQL
        ```SQL
            SELECT * FROM table_name;
        ```
2. Animals
    1. Cheetah
    2. Buffalo
    3. Duck 
    > I love ducks. They are cute.

---


*Note*: You can mix ordered and unordered list

1. First Item
2. Second Item
    - some item
    - next item

---

- List Item
    1. First 
    2. Second
- List Item

---

## How to write reference links?

1. First write the link text in square bracket followed by colon.
2. Then write the link address.
3. Third, add one space and write reference text inside quotes.
4. Use the link text and reference text inside square bracket where you want to test it.



**Example**:

Use [Bing][msb] to make serches.

[msb]:https://www.bing.com/ "Bing"

---

## Automatic links

Websites can be refereced with their regular address.
https://www.instagram.com/

Email addresses can be linked using angle brackets.

<donotreply@ymail.com>

---

## Line Images vs Referenced Images

### Line Images

![My Doll House](mydollhouse.jpg)

### Referenced Images

![Smiley Plushies][Happy Emojis]

[Happy Emojis]:https://images.pexels.com/photos/207983/pexels-photo-207983.jpeg "Smiley Plushies"

---

## Inline HTML

Sometimes you need to add  some inline HTML.

<dl>
  <dt>Markdown</dt>
  <dd>An awesome plain text format.</dd>
</dl>

>*Notice that the inline HTML did not require any of the HTML tags that you typically have to associate with a full blown HTML document. we just put in the snippet of html that we want. And after the inline HTML I can continue on with my Markdown file.*
### Jason Taylor

---

## Fenced Code blocks

``` java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Markdown!");
    }
}

```
---

##  Exporting Markdown Files

StackEdit offers multiple ways to export your Markdown documents.

---


