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

#### Checklists (Task Lists):
`[⋅] Unchecked Item`    Dots indicate spaces    <br>
`[X] Checked Item`    <br>

#### Code Blocks:
\`inline code.\`                        <br>
\```This is a fenced code block.\```    <br>
⋅⋅⋅⋅This is also a fenced code block.     <br>

#### Emphasis:
&nbsp;&nbsp;&nbsp;&nbsp; `*Italic*`    <br>
&nbsp;&nbsp;&nbsp;&nbsp; `**Bold**`    <br>

#### Escaping Characters:
Use `\*don't italicize this\*` to escape asterisks inside italic block, as shown below:   <br>
\*don't italicize this\*   <br>


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
&nbsp;&nbsp;&nbsp;&nbsp;  `1. Numbered Item`                              <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `⋅⋅* Bulleted Item`    # Dots indicate spaces    <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `⋅⋅* Bulleted Item`    # Dots indicate spaces    <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `2. Numbered Item`                              <br>


#### Strikethrough:
&nbsp;&nbsp;&nbsp;&nbsp; `~~Strikethrough~~`    <br>






#### Reference:    <br>
[https://beegit.com/markdown-cheat-sheet](https://beegit.com/markdown-cheat-sheet) <br>
[http://nestacms.com/docs/creating-content/markdown-cheat-sheet](http://nestacms.com/docs/creating-content/markdown-cheat-sheet) <br>
[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) <br>
[https://medium.com/ibm-data-science-experience/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed](https://medium.com/ibm-data-science-experience/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed) <br>
