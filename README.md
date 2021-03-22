Markdown Cheatsheet<a name="TOP"></a>
===================

- - - - 
# Heading 1 #

    Markup :  # Heading 1 #

    -OR-

    Markup :  ============= (below H1 text)

## Heading 2 ##

    Markup :  ## Heading 2 ##

    -OR-

    Markup: --------------- (below H2 text)

### Heading 3 ###

    Markup :  ### Heading 3 ###

#### Heading 4 ####

    Markup :  #### Heading 4 ####


Common text

    Markup :  Common text

_Emphasized text_

    Markup :  _Emphasized text_ or *Emphasized text*

~~Strikethrough text~~

    Markup :  ~~Strikethrough text~~

__Strong text__

    Markup :  __Strong text__ or **Strong text**

___Strong emphasized text___

    Markup :  ___Strong emphasized text___ or ***Strong emphasized text***

[Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

    Markup :  [Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

[heading-1](#heading-1 "Goto heading-1")
    
    Markup: [heading-1](#heading-1 "Goto heading-1")

Table, like this one :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

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

```
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

`code()`

    Markup :  `code()`

```javascript
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
```

    Markup : ```javascript
             ```

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

~~~
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup : - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2 
~~~

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered

~~~
 Markup : 1. A numbered list
              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
~~~

- [ ] An uncompleted task
- [x] A completed task

~~~
 Markup : - [ ] An uncompleted task
          - [x] A completed task
~~~

- [ ] An uncompleted task
    - [ ] A subtask

~~~
 Markup : - [ ] An uncompleted task
              - [ ] A subtask
~~~

> Blockquote
>> Nested blockquote

    Markup :  > Blockquote
              >> Nested Blockquote

_Horizontal line :_
- - - -

    Markup :  - - - -

_Image with alt :_

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

    Markup : ![picture alt](http://via.placeholder.com/200x150 "Title is optional")

Foldable text:

<details>
  <summary>Title 1</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>
<details>
  <summary>Title 2</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>

    Markup : <details>
               <summary>Title 1</summary>
               <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
             </details>

```html
<h3>HTML</h3>
<p> Some HTML code here </p>
```

Link to a specific part of the page:

[Go To TOP](#TOP)
   
    Markup : [text goes here](#section_name)
              section_title<a name="section_name"></a>    

Hotkey:

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    Markup : <kbd>⌘F</kbd>

Hotkey list:

| Key | Symbol |
| --- | --- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1:  Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    Markup : Code appears between colons :EMOJICODE:


Adding Icons with links:

    Markup : [<code>
             <img alt= "alt text" width="26px" src="the/image/source">
             </code>](insert redirect link here, which will take the user to the specify website when the icon is clicked)
             
             You can use a <br> tag after the above snippet to insert icons on a next line
             
             This is basic HTML.
            
You can get or embed pixel perfect free icons from [icons8.com](https://icons8.com/icons)

[<code>
<img alt="java" width="26px" src="https://img.icons8.com/color/240/000000/java-coffee-cup-logo.png">
</code>](https://docs.oracle.com/en/java/)
[<code>
<img alt="spring" width="26px" src="https://img.icons8.com/color/240/000000/spring-logo.png">
</code>](https://spring.io/projects/spring-framework)
[<code>
<img alt="javascript" width="26px" src="https://img.icons8.com/color/240/000000/javascript.png" />
</code>](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[<code>
<img alt="react" width="26px" src="https://img.icons8.com/color/240/000000/react-native.png" />
</code>](https://reactjs.org/)
[<code>
<img alt="python" width="26px" src="https://img.icons8.com/color/240/000000/python.png">
</code>](https://www.python.org/)
[<code>
<img alt="MySQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png">
</code>](https://dev.mysql.com/)
[<code>
<img alt="postgresql" width="26px" src="https://img.icons8.com/color/240/000000/postgreesql.png">
</code>](https://www.postgresql.org)
[<code>
<img alt="Firebase" width="26px" src="https://img.icons8.com/color/48/000000/firebase.png">
</code>](https://firebase.google.com)
[<code>
<img alt="Flutter" width="26px" src="https://img.icons8.com/color/48/000000/flutter.png">
</code>](https://flutter.dev)
[<code>
<img alt="Git" width="26px" src="https://img.icons8.com/color/240/000000/git.png">
</code>](https://git-scm.com/)
[<code>
<img alt="visual studio code" width="26px" src="https://img.icons8.com/fluent/240/000000/visual-studio-code-2019.png" />
</code>](https://code.visualstudio.com/)
[<code>
<img alt="pycharm" width="26px" src="https://img.icons8.com/color/240/000000/pycharm.png" />
</code>](https://www.jetbrains.com/pycharm/)
[<code>
<img alt="intellij idea" width="26px" src="https://img.icons8.com/color/240/000000/intellij-idea.png" />
</code>](https://www.jetbrains.com/idea/)
