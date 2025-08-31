# Obsidian cheat sheet and shortcuts 
This repository contains all the basic cheatsheets you need to get started to make notes in [obsidian](https://obsidian.md/). If something's missing, add yours by raising an issue here. ^_^

> I am using [Things theme](https://github.com/colineckert/obsidian-things) in the screenshots below.
### Quick Tips:
- **To Search for a specific note**: Use Ctrl + P (Cmd + P on Mac).
- **For Internal Links**: Use `[[note name]]` to create internal links to other notes.
- **For External Links**: Use `[Text](URL)` to create external links.
- **For Bullet Points**: Use `-`, `*`, or `1`.
- **For Headings**: Use `#` (e.g., # Heading 1, ## Heading 2).
- **For Code Blocks**: Wrap text in triple backticks `(```)`.
- **For Embeds**: Use `![[note name]]` to embed another note in your current note.

 

| Word Formatting, Lists & Blockquotes                                                      | Links, Code Blocks, Tables & Footnotes                                                    |
| ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| ![image](https://github.com/user-attachments/assets/3127cf70-2e9b-4e51-b004-c31c7d59b007) | ![image](https://github.com/user-attachments/assets/9e8d23cb-465e-4e96-9df3-ed3aa9a64174) |


--- 

## Obsidian Markdown Syntax

<div align="center" style="background-color:#f4f4f4; padding:6px; border-radius:6px; font-weight:bold;color:blue">
Quick Overview:
</div>
<br>


```
Headers:
# H1
## H2
### H3
#### H4
##### H5
###### H6

Emphasis:
_italic text_
**bold text**
_**bold italic text**_
~~strikethrough text~~
==Highlights==

Lists:
Unordered -
- Item 1
- Item 2
Ordered - 
1. Item 1
2. Item 2

> This is a blockquote.

Horizontal Line / Separator: ---

Links:
[link text](https://example.com/)

Images:
![Alt Text](image-url)

Code:
Inline - `code`
Block -
    ```
        code
    ```

Tasks
- [x] Task completed
- [ ] Task not completed

> Quotes/ Blockquotes

[^1]: footnote
```
<div align="center" style="background-color:#f4f4f4; padding:6px; border-radius:6px; font-weight:bold;color:blue">
Detailed Overview:
</div>

# Heading 1:
 
```
# Heading 1
```


## Heading 2:

```
## Heading 2
```

**Line Break**:

```
---
```

- Bullet Points:

``` 
- Bullet 
```

1. Numbered List:

``` 
1. one
2. two
```

- [X] Checklist:

```
- [x] list 
```

**Bold**:

```
**text**
```

*Italic*:

```
*text*
```

***Italic Bold***:

```
***text***
```

~~Strikethrough~~:

```
~~this text is crossed out~~
```

<mark>Highlights</mark>:

```
==this text is highlighted==
```


**```Code Blocks```**:

```
By putting 3 (```) signs before and after the code.
``` code ```
```

**[[Links]]**:

```
[link](sources)
```

Images:

```
![Alt Text](https://example.com/image.png)
```

Blockquotes:

> Quotes/ Blockquotes

```
> this is a quote.
```


Tables:

| Table Cell A | Table Cell B |
| ------------ | ------------ |
| Text         | Text         |


```
| Table Cell A | Table Cell B |
| ------------ | ------------ |
| Text         | Text         |
```

Tables with Alignment:
| Left Align | Center Align | Right Align |
| :--------- | :----------: | ----------: |
| Text       |     Text     |        Text |

```
| Left Align | Center Align | Right Align |
| :--------- | :----------: | ----------: |
| Text       |     Text     |        Text |

```

Footnotes (like this[^1]): 

```
[^1]: This is the footnote you usually add at the bottom of your notes.
```
[^1]: This is a footnote.


<details>
These are super handy for big markdown files!
<summary> Collapsible Sections (Click to expand):
</summary>
</details>

```
<details>
<summary>Toggle to Expand</summary>
hidden content
</details>
```

**Callouts**:
```
> [!note]  
> This is a note callout.  

> [!tip]  
> This is a tip callout.  

> [!warning]  
> Be careful with this.  
```

For a comprehensive guide on callouts, see [Obsidian’s official documentation](https://help.obsidian.md/Callouts).



**Emoji**:

By default, Obsidian does not support `:emoji:` shortcodes. To use them, you can install this awesome community plugin: [Emoji Shortcodes](https://github.com/phibr0/obsidian-emoji-shortcodes).  


**Input:** `:smile: :rocket: :tada:`

**Output:** :smile: :rocket: :tada:

---


## Obsidian Shortcuts
<div align="center" style="background-color:#f4f4f4; padding:6px; border-radius:6px; font-weight:bold;color:blue">
General Shortcuts:
</div>
<br>

| Shortcut (Win/Linux) | Shortcut (Mac)     | Function                     |
| -------------------- | ------------------ | ---------------------------- |
| Ctrl + S             | Cmd + S            | Save the file                |
| Ctrl + N             | Cmd + N            | Create a new note            |
| Ctrl + P             | Cmd + P            | Open command palette         |
| Ctrl + O             | Cmd + O            | Open quick switcher          |
| Ctrl + Shift + F     | Cmd + Shift + F    | Search in all files          |
| Ctrl + G             | Cmd + G            | Open graph view              |
| Ctrl + Alt + ←       | Cmd + Alt + ←      | Navigate back                |
| Ctrl + Alt + →       | Cmd + Alt + →      | Navigate forward             |
| Ctrl + F             | Cmd + F            | Search in current file       |
| Ctrl + H             | Cmd + H            | Find/Replace in current file |
| Ctrl + E             | Cmd + E            | Toggle edit/preview modes    |
| Ctrl + ,             | Cmd + ,            | Open settings                |
| Ctrl + Tab           | Ctrl + Tab         | Next tab                     |
| Ctrl + Shift + Tab   | Ctrl + Shift + Tab | Previous tab                 |
| Alt + Tab            | Cmd + Tab          | Next app                     |
| Alt + Shift + Tab    | Cmd + Shift + Tab  | Previous app                 |
| Win + Tab            | Mission Control    | Task view                    |
| Win + Shift + Tab    | Mission Control    | Next window                  |

<br>
<div align="center" style="background-color:#f4f4f4; padding:6px; border-radius:6px; font-weight:bold;color:blue">
Editing  Shortcuts:
</div>
<br>

| Shortcut (Win/Linux) | Shortcut (Mac)      | Function                  |
| -------------------- | ------------------- | ------------------------- |
| Ctrl + B             | Cmd + B             | Bold selected text        |
| Ctrl + I             | Cmd + I             | Italicize selected text   |
| Ctrl + K             | Cmd + K             | Insert external link      |
| Ctrl + ]             | Cmd + ]             | Indent                    |
| Ctrl + [             | Cmd + [             | Unindent                  |
| Ctrl + D             | Cmd + D             | Delete current line       |
| Ctrl + V             | Cmd + V             | Duplicate current line    |
| Ctrl + Click         | Cmd + Click         | Open note in current pane |
| Ctrl + Shift + Click | Cmd + Shift + Click | Open note in new pane     |
| Ctrl + P             | Cmd + P             | Quick search              |
| Ctrl + N             | Cmd + N             | New note                  |
| Ctrl + Shift + D     | Cmd + Shift + D     | Create a daily note       |
| Ctrl + /             | Cmd + /             | Toggle command palette    |
| Ctrl + E             | Cmd + E             | Open graph view           |



Hope this helps you get more out of Obsidian!

<a href='https://ko-fi.com/C1C73CUZM' target='_blank'><img height='38' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>