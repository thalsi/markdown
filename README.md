# Markdown

1. What is markdown language? Why? Where?
    - Markdown is a opensource,lightweight and mrakup language.
    - Plan text that converts to a Rich HTML document.
    - Rich Text is a format for storing documents. look like DOC or ODT
    - If you need advanced functionality with flexible styling options or you want to use a fancy email signature, use the HTML format. If you're only looking for adjustable text options, such as italics or bolding, use the Rich Text format. When you just want text and no other options, you can use the Plain Text format.
2. What is markup language? 
    - markup is a text-encoding system. used to stucture and format text.

3. What is text-encoding system? 
    - Endcoding is a method or process of coverting a series of characters.letters, numbers, punctuation, and symbols into a special or unique format for transmission or storage in computers. Data is represented in computers using ASCII, UTF8, UTF32, ISCII, and Unicode encoding schemes. 

4. where is use markdown language?
    - Markdown is widely used for blogging, documentation pages and readme files.
 
## File Extension
- .markdown
- .md
- .mkd
- .mkdown
- .mdown
- .text
   
## Cheat sheet

1. Basic syntax
    1. Heading (6)
    2. Bold (2)
    3. Italic (2)
    4. Blockquote
    5. Ordered List
    6. Unordered List (3)
    7. code (2)
    8. Horizontal Rule (3)
    9. Link 
        - link
        - bold link 
        - italic link
        - section link
        - declaration link
    10. Image
        - Image
        - declaration link
    11. URLs and Addresses

2. Extended syntax
    1. Table
        1. normal
        2. Alignemnt table (3)
    2. Fenced code block (2)
    3. Footnote
    4. My Great heading
    5. Definition List
    6. Strikethrough
    7. Task List
    8. Emoji
    9. Highlight
    10. Subscript
    11. Superscript
    12. Automatic URL linking
    13. Diabling Automatic URL linking


## Basic syntax

1. Heading
    # Heading
    ## Heading
    ### Heading
    #### Heading
    ##### Heading
    ###### Heading

2. Bold
    1. **Bold text**
    2. __Bold text__

3. Italic
    1. *Italic text*
    2. _Italic text_

4. Blockquote
    > "Write a short blockquote here."

5. Ordered list
    1. Item 1
    2. Item 2
        1. Item 2.1
        2. Item 2.2
    3. Item 3
    4. Item 4

6. Unordered list
    - item 1
    - item 2
        - item 1
        - item 2
    - item 3

    * item 1
    * item 2
    * item 3

    + item 1
    + item 2
    + item 3

7. Code

` Javascprit is a most popular language let a=0; b=4;`

``Please use this `consloe.log()` for the debuging``

8. Horizontal rule

---
___

***

9. Link
- [google](https://www.google.com)
- **[google](https://www.google.com)**
- *[google](https://www.google.com)*
- [`Basic section navigate`](#basic-syntax)

- Here click link [Google link]
- Here click link [Facebook link]

[Google link]: https://www.google.com
[Facebook link]: https://www.facebook.com

10. Image
- ![cat](./assets/images/cat.jpg)

- declation image [Cat image][cat]
- declation url image [Url image][url image]

[cat]:./assets/images/cat.jpg
[url image]:https://octodex.github.com/images/founding-father.jpg


11. URLs and Email Addresses

<https://www.google.com>

<myemail@gmail.com>


## Extended Synstx
These elements extend the basic syntax by adding additional features.
Not all markdown applications support these elements.

1. Table

| Title | Descption |
|-------|-----------|
| Auun  | Kids      |
| Ali   | Kids      |

| Id | Title | Genter |
|:---| :---: |    ---:|
| 1  | Annu  | Female |
| 2  | Ali   | Male   |

2. Fenced Code block

```
{
    id:2,
    title:name
}
```

~~~
{
    id:2,
    name:ali mon
}
~~~

3. Footnote

Footnote here click here [^1] [^2] [^google]

[^1]: This is a footnote 1
[^2]: This is a footnote 2
[^google]: Google is a sreach engg

4. My great heading 

#### My Custom Heading {#custom-id}
- here click to custom id set link:
<h4>custom-id use linking here .plase click here</h4>

5. Definition List

<dl>
<dt>Heading 1</dt>
    <dd>Despction for the heading 1</dd>
<dt>Heading 2</dt>
    <dd>Despction for the heading 2</dd>
</dl>

6. Strikethrough

~~ delete this line ~~

7. Task list

[x] Task 1
[] Task 2
[x] Task 3

8. Emoji
- This is Emoji :joy:
- [Emoji is here](https://emojipedia.org/)

9. Highlight
 This line is ==Highlight== 

10. Subscrpit
H~2~O

11. Superscprit
X^2^

12. Automatic URL Linking
https://www.google.com

13. Disabling Automatic URL linking
`https://www.google.com`


