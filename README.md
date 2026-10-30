<a name="TOP"></a>
![picture alt](https://placehold.co/1000x100/transparent/999?text=Markdown%20Cheatsheet&font=source-sans-pro "Markdown Cheatsheet")

# 📝 Typography

# Heading 1

Markup :

    # Heading 1

Alternative markup :

    ============= (below H1 text)

## Heading 2

Markup :

    ## Heading 2

Alternative markup :  

    --------------- (below H2 text)

### Heading 3

Markup :

    ### Heading 3

#### Heading 4

Markup :
    
    #### Heading 4


Common text

Markup :

    Common text

_Emphasized text_

Markup :

    _Emphasized text_ or *Emphasized text*

~~Strikethrough text~~

Markup :

    ~~Strikethrough text~~

__Strong text__

Markup :

    __Strong text__ or **Strong text**

___Strong emphasized text___

Markup :

    ___Strong emphasized text___ or ***Strong emphasized text***

[Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

Markup :  

    [Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

[Link to heading](#heading-1 "Goto heading-1") or [Link to section](#TOP)

Markup:

    [Link to heading](#heading-1 "Goto heading-1") or [Link to section](#TOP)

# 🧮 Tables

A standard table

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Markup :

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

Adding a pipe `|` in a cell :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | \|

Markup :

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \| 
```

Left, right and center aligned table

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

Markup :

```
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

# 👩‍💻 Code

Inline code

`code()`

Markup :

    `code()`

Code block

```javascript
var myGreatVariable = 'test'
```

Markup :
    
    ```javascript
    var myGreatVariable = 'test'
    ```

# 📜 Lists

Unordered list

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

Markup :

    * Bullet list
        * Nested bullet
            * Sub-nested bullet etc
    * Bullet list item 2

Alternative markup :

    - Bullet list
        - Nested bullet
            - Sub-nested bullet etc
    - Bullet list item 2 

Numbered list

1. A numbered list
    1. A nested numbered list
    1. Which is numbered
1. Which is numbered

Markup :

    1. A numbered list
        1. A nested numbered list
        2. Which is numbered
    2. Which is numbered

Alternative markup (*the numbering is automatic*):

    1. A numbered list
        1. A nested numbered list
        1. Which is numbered
    1. Which is numbered

Task list

- [ ] An uncompleted task
- [x] A completed task
  - [ ] A subtask

Markup :

    - [ ] An uncompleted task
    - [x] A completed task
        - [ ] A subtask

# 🗣️ Quoting

> Blockquote
>> Nested blockquote

Markup :

    > Blockquote
    >> Nested Blockquote

Footnotes (*see end of README*)

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: A reference.
[^2]: To add line breaks within a footnote, Add a carriage return and prefix the new line with 4 spaces.

    This is a second line.

Markup :

```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, Add a carriage return and prefix the new line with 4 spaces.

    This is a second line.
```

# 🖼️ Media / Emojis

Image with alt :

![picture alt](https://placehold.co/600x200?text=placeholder "Title is optional")

Markup :

    ![picture alt](https://placehold.co/600x200 "Title is optional")

Emoji

:exclamation: Use emoji icons to enhance text. :+1: Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

Markup (*Emoji slug should appear between colons*):

    :+1: :exclamation:

# ⁉️ Alerts

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

Markup :

```
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.
```

> [!TIP]
> Optional information to help a user be more successful.

Markup :

```
> [!TIP]
> Optional information to help a user be more successful.
```

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

Markup :

```
> [!IMPORTANT]  
> Crucial information necessary for users to succeed.
```

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

Markup :

```
> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.
```

> [!CAUTION]
> Negative potential consequences of an action.

Markup :

```
> [!CAUTION]
> Negative potential consequences of an action.
```

# 💬 Misc

<details>
  <summary>Foldable text</summary>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
</details>

<br>

Markup :

    <details>
        <summary>Title 1</summary>
        <p>Lorem ipsum dolor sit amet, ...</p>
    </details>


Hotkey

<kbd>⌘F</kbd>

Markup : 

    <kbd>⌘F</kbd>

*Hotkey symbols handy list below*

| Key | Symbol | Key | Symbol |
| --- | --- | --- | --- |
| Option | ⌥ | Power | ⌽ |
| Control | ⌃ | Return | ↩ |
| Command | ⌘ | Delete | ⌫ |
| Shift | ⇧ | Up | ↑ |
| Caps Lock | ⇪ | Down | ↓ |
| Tab | ⇥ | Left | ← |
| Esc | ⎋ | Right | → |

Horizontal line

- - - -

Markup :

    - - - -

Inline mathematical equation $F(x) = \int^a_b \frac{1}{3}x^3$

Markup :

    $F(x) = \int^a_b \frac{1}{3}x^3$

Block mathematical equation

$$P \left( A=2 \, \middle| \, \dfrac{A^2}{B}>4 \right)$$

Markup :

    $$P \left( A=2 \, \middle| \, \dfrac{A^2}{B}>4 \right)$$
