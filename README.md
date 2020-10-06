# What is Markdown?
- a lightweight markup language with a plain text formatting syntax
- can be converted to html/xhtml and other formats
- it's main purpose is readability and ease of use

# What is it used for?
- README files (Github)
- Forum and Blog Posts
- Static sites generators
- Presentations

# What can we format with MD?
- Headings
- Lists
- Emphasis
- Links
- Blocks of code
- Images
- Quote blocks
- Horizontal rules

# What do I need to run markdown
- any text editor is good for markdown, choose one with extensions to see live preview of the file (es. vs code)
- or a Chrome extension [Markdown Viewer](https://chrome.google.com/webstore/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk/) for local/remote files

# How to I comment in a markdown file?
- html comments are compatible with markdown
<!-- i.e. this will not show in the preview -->

# Headings
- Use hashtag to add heading levels (from one to six #,##,###,####,#####,######)

# Italics
- To use italics we have two options:
    1. Use asterisk *this is italics*
    2. Use underscores _this is italics too_ 

# Strong
- To use bold characters we also have two options:
    1. Use double asterisk **this is a bold statement**
    2. Use double underscores __this is a blunt one too__ 

# Strikethrough
- To strike characters we use double ~~tilde~~

# Horizontal Rule
- An horizontal rule is a separator, to make it we have two options:
    1. Triple hyphens ---
    2. Triple underscores ___
___

# Escape Characters
- In some cases we want to escape a character used by Markdown, in that case we use \ to show the actual special character.
- In example \*\*this will not show in bold\*\*

# Block Quote
- To create a block quote we use the \> symbol
> This is a quote inside a block. 

# Links
- For links the text we wanna show goes into brackets \[\] while the URL address we want to point goes inside \(\)
- i.e. [Google](https://google.com)
- To add a title when we hover the link we can just add "Title" after the URL address
- i.e. [Google](https://google.com "Google.com")

# Lists
## Unordered lists
- ul can be displayed using \* for each item
* item 1
    * item 1.1
* item 2
    * item 2.1
* item 3

## Ordered lists
- ol can be shown using n. before each item
1. Hello
    1. World
1. My name
1. How are you?

# Inline Code Block
- We use backticks 
- `import time`

# Images
- very similar to links but with a ! before the square brackets
- ![Unsplash](https://unsplash.com/photos/xrVDYZRGdw4/download?force=true&w=640)

# Github
- gh has its own flavor of markdown
- for block of codes use triple backticks instead of one \`\`\` 
- we can also add specific syntax for the language we want to use

```JavaScript
import React
const elem = () => {
    return(
        "This is something"
    )
}
export defaults elem
```

```Python
from datetime import datetime
dt = datetime(2020,10,1,12)
def getTime(dt):
    return dt.Hour
```

# Tables
| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

# Task list
- These shows as checkbox on GH
*[x] Task 1
*[x] Task 2
*[ ] Task 3
