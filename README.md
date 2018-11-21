# 📋 📘 Boostnote Markdown CheatSheet - Preview!


The missing one page markdown feature cheat sheet for [Boostnote](https://boostnote.io/).
It's tries to give a short summery of all formatting options which are available in Boostnote.

---
:warning: This is the **Preview Page** to see how it's rendered.

:point_right: Open the [Cheat Sheet](BOOSTNOTE_MARKDOWN_CHEAT_SHEET.md) to see the code.

---

<!-- toc -->

- [Text Formatting](#Text-Formatting)
  * [Emphasis](#Emphasis)
  * [Abbreviation](#Abbreviation)
  * [Superscript](#Superscript)
  * [Link](#Link)
  * [Check box](#Check-box)
  * [Quotation](#Quotation)
  * [Footnotes](#Footnotes)
  * [Html](#Html)
  * [Emotiocons](#Emotiocons)
  * [Arrows](#Arrows)
  * [Keystrokes](#Keystrokes)
  * [Source Code](#Source-Code)
- [Structuring](#Structuring)
  * [List](#List)
  * [Definition list](#Definition-list)
  * [Table](#Table)
  * [Block](#Block)
  * [Fold](#Fold)
  * [Horizontal line](#Horizontal-line)
  * [Admonition](#Admonition)
- [Image](#Image)
- [Latex](#Latex)
- [Diagram Integrations](#Diagram-Integrations)
  * [Flowchart](#Flowchart)
  * [Sequence](#Sequence)
  * [mermaid](#mermaid)
  * [Chart](#Chart)
  * [Ditaa](#Ditaa)
  * [Plant UML](#Plant-UML)

<!-- tocstop -->
> *Table of Contens generated by:*
> `Shortcut:` [[Shift]]+[[ctrl]]+[[T]]
> `Menu:`  _File / Generate / Update Markdown TOC_

## Text Formatting

### Emphasis
*Italic type*
**Bold**
~~Negative~~
`highlighted`

### Abbreviation
The HTML specification
is maintained by the W3C.
*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium

### Superscript
![mermaid](attachments/superscript.png?raw=true)

### Link
[Boostnote](https://boostnote.io)

### Check box
- [x] Task 1
- [ ] Task 2

### Quotation
> Quotation
> Quotation Quotation

### Footnotes
Here is a footnote reference, <sup>[1](#myFootNote)</sup>
and another <sup>[2](#anotherFootNote)</sup>.

### Html
<span style="color:green">Green Text</span>
<span style="color:yellow">Yellow Text</span>
<u>underlined</u>
> HTML only works if you enable:
> Menu: _Preferences / Interface / Sanitastion / Enable dangerous html tags_

### Emotiocons
Emoji by shortcode: :books: :memo: :eyes:
Emoji by Unicode:   📚 📝 👀
[complete emojy list](https://www.webpagefx.com/tools/emoji-cheat-sheet/)

### Arrows
⟶
⟵
⟷

### Keystrokes
![latex](attachments/keystrokes.png?raw=true)

### Source Code

``` js
Render: function () {
  Return (
    <Div className = “commentBox”>
      <H1> Comments </ h1>
      <CommentList data = {this.state.data} />
      <CommentForm onCommentSubmit = {this.handleCommentSubmit} />
    </Div>
  );
}
```

## Structuring

### List
* List 1
* List 2
1. First ordered list item
 Second line
2. Another item

### Definition list

Term 1
~ Definition 1
Term 2
~ Definition 2a
~ Definition 2b
Term 3
~

Term 1
: Definition 1
Term 2 with \*inline markup\*
: Definition 2

         { some code, part of Definition 2 }
    Third paragraph of definition 2.

### Table
| Tables        | Are           | Cool  |
| :------------ |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
|             |          Grouping           ||

![flowchart](attachments/table.png?raw=true)

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

> There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

### Block
	Some Infor First Line - Lorem ipsum dolor sit amet, consetetur sadipscing eli
	Some Infor Second Line - Lorem ipsum dolor sit amet, consetetur sadipscing eli
	Some Infor Third Line - Lorem ipsum dolor sit amet, consetetur sadipscing eli

### Fold
<details><summary>Boostnote is a notepad corresponding to markdown notation, which is a tool for organizing and sharing information.</summary>
- Features - <br>
· Search function to find memos in one shot
· Supports markdown notation <br>
· Support for Mac, Windows, Linux, iOS, Android <br>
· Export and import to Plain text (.txt), Markdown (.md) format <br>
· Supports PDF saving <br>
· Can be used offline <br>
· Synchronize to dropbox etc. with setting <br>
* Supports theme colors and numerous fonts<br>
</details>
</details>

### Horizontal line
Horizontal lines have various ways of writing.
* * *
***
---

### Admonition

![admonition](attachments/admonition.png?raw=true)

## Image

![images](attachments/images.png?raw=true)

[logo]: https://boostnote.io/assets/img/logo.png "Boostnote Logo"

## Latex

![latex](attachments/latex.png?raw=true)

## Diagram Integrations

### Flowchart

![flowchart](attachments/flowchart.png?raw=true)

### Sequence

![sequence](attachments/sequence.png?raw=true)

### [mermaid](https://mermaidjs.github.io/)

![mermaid](attachments/mermaid.png?raw=true)


### Chart

![chart](attachments/chart.png?raw=true)

### [Ditaa](http://ditaa.sourceforge.net/)

![ditaa 1](attachments/ditaa_1.png?raw=true)

![ditaa 2](attachments/ditaa_2.png?raw=true)


### [Plant UML](http://plantuml.com/)

![plantuml 1](attachments/plantuml_1.png?raw=true)

![plantuml 2](attachments/plantuml_2.png?raw=true)

---

<a name="myFootNote">1</a>: Here’s one with multiple blocks.

<a name="anotherFootNote">2</a>: Subsequent paragraphs are indented to show that they belong to the previous footnote.