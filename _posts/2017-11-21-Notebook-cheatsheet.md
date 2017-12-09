---
layout: post
title: Markdown Cheatsheet for Jupyter Notebook
tags: [Markdown, LJupyter Notebook, Python]
---

This post is created as a quick reference to assist Markdown users to get a better writting experience in Jupyter Notebook.<br>

#### Markdown Skills Covered on this Page
* Adding Image
* Adding Link
* Alighning Text
* Blockquotes
* Bulleted List
* Change Font Type and Size
* Checklists (Task Lists)
* Code Blocks
* Emphasis
* Escaping Characters
* Headers
* Highlighting
* Horizontal Line
* Indenting Lines
* Numbered List
* Nested List
* Strikethrough
* Superscript and Subscript
* Table
<br>
<br>
<br>


#### Adding Image:
&nbsp;&nbsp;&nbsp;&nbsp; `![Image Text](/path/to/image.jpg)`            <br>
&nbsp;&nbsp;&nbsp;&nbsp; `![Image Text](/path/to/image.jpg "Title")`    <br>

#### Adding Link:
&nbsp;&nbsp;&nbsp;&nbsp; `[Link Text](https://www.google.com/)`    <br>

#### Aligning Text:
Aligning text in native markdown is not possible. However, you can align the text using inline HTML tags. For example, you can use `<div style="text-align: right"> show-the-text-to-the-right </div>` to align the text to the right. The outcome is as follows:
<div style="text-align: right"> show-the-text-to-the-right </div>

Use `<div style="text-align: center"> show-the-text-in-the-middle </div>` to put the text in the middle. It renders to:
<div style="text-align: center"> show-the-text-in-the-middle </div>
<br>

#### Blockquotes:
&nbsp;&nbsp;&nbsp;&nbsp; `> Blockquote`            <br>
&nbsp;&nbsp;&nbsp;&nbsp; `>> Nested blockquote`    <br>

#### Bulleted List:
&nbsp;&nbsp;&nbsp;&nbsp; `* Bulleted Item`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `- Bulleted Item`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `+ Bulleted Item`    <br>

#### Change Font Type and Size:
Use the following code to change font type and size in markdown:          <br>
&nbsp;&nbsp;&nbsp;&nbsp; `<span style="color: #f2cf4a; font-family: Arial; font-size: 10pt;">change-font-type-and-size, Arial, 10pt</span>`  <br>
&nbsp;&nbsp;&nbsp;&nbsp; `<span style="color: #e40040; font-family: Arial; font-size: 20pt;">change-font-type-and-size, Arial, 20pt</span>`  <br>
<br>
It renders to:          <br>
&nbsp;&nbsp;&nbsp;&nbsp; <span style="color: #1E824C; font-family: Arial; font-size: 10pt;">change-font-type-and-size, Arial, 10pt</span>  <br>
&nbsp;&nbsp;&nbsp;&nbsp; <span style="color: #e40040; font-family: Arial; font-size: 20pt;">change-font-type-and-size, Arial, 20pt</span>  <br>

#### Checklists (Task Lists):
&nbsp;&nbsp;&nbsp;&nbsp; `[⋅] Unchecked Item`      Dots indicate spaces    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `[X] Checked Item`    <br>

#### Code Blocks:
```
    `This is inline code.`                                     
    ```This is a fenced code block.```                            
    ⋅⋅⋅⋅This is also a fenced code block.      # Dots indicate spaces   
```


#### Emphasis:
&nbsp;&nbsp;&nbsp;&nbsp; `*Italic*`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `**Bold**`    <br>

#### Escaping Characters:
Use `\*don't italicize this\*` to escape asterisks inside italic block, as shown below:   <br>
&nbsp;&nbsp;&nbsp;&nbsp; \*don't italicize this\*   <br>


#### Headers:
&nbsp;&nbsp;&nbsp;&nbsp; `# h1 Heading`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `## h2 Heading`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `### h3 Heading`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `#### h4 Heading`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `##### h5 Heading`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `###### h6 Heading`    <br>

#### Highlighting:
You can use HTML to highlight text in markdown. For example, using `<span style="background-color: #FFFF00">Text-to-be-highlighted</span>` in markdown will generate:    <br>
&nbsp;&nbsp;&nbsp;&nbsp; <span style="background-color: #FFFF00">Text-to-be-highlighted</span>    <br>

#### Horizontal Line:
&nbsp;&nbsp;&nbsp;&nbsp; `***  three consecutive asterisks `      <br>
&nbsp;&nbsp;&nbsp;&nbsp; `---  three consecutive dashes `         <br>
&nbsp;&nbsp;&nbsp;&nbsp; `___  three consecutive underscores `    <br>

#### Indenting Lines:
Markdown allows inline HTML, so writing `&nbsp;&nbsp;&nbsp;&nbsp;text` will 4 space characters in front of `text`, as shown below: <br>
&nbsp;&nbsp;&nbsp;&nbsp;text    <br>

#### Numbered List:
&nbsp;&nbsp;&nbsp;&nbsp; `1. Numbered Item 1`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `2. Numbered Item 2`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `3. Numbered Item 3`    <br>

#### Nested List:
&nbsp;&nbsp;&nbsp;&nbsp;  `1. Numbered Item`                            <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `⋅⋅* Bulleted Item`    Dots indicate spaces    <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `⋅⋅* Bulleted Item`    Dots indicate spaces    <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `2. Numbered Item`                            <br>


#### Strikethrough:
&nbsp;&nbsp;&nbsp;&nbsp; `~~Strikethrough~~`    <br>

#### Superscript and Subscript:
Use the `<sup>text</sup>` for superscripts. For example, if you type `O(n<sup>2</sup>)`, you will get: <br>
&nbsp;&nbsp;&nbsp;&nbsp;  O(n<sup>2</sup>)     <br>
<br>
`<sub>text</sub>` is the equivalent for subscripts. <br>

#### Table:
```
| First Header  | Second Header | Second Header | Second Header |
| ------------- | ------------- | ------------- | ------------- |
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |
```

Use the following format to create a table:     <br>
| First Header  | Second Header | Second Header | Second Header |     <br>
| ------------- | ------------- | ------------- | ------------- |     <br>
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |     <br>
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |     <br>
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |     <br>


It renders to: <br>

| First Header  | Second Header |  Third Header | Fourth Header |
| ------------- | ------------- | ------------- | ------------- |
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  | Content Cell  |



#### Reference:    <br>
[https://beegit.com/markdown-cheat-sheet](https://beegit.com/markdown-cheat-sheet) <br>
[http://nestacms.com/docs/creating-content/markdown-cheat-sheet](http://nestacms.com/docs/creating-content/markdown-cheat-sheet) <br>
[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) <br>
[https://medium.com/ibm-data-science-experience/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed](https://medium.com/ibm-data-science-experience/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed) <br>
