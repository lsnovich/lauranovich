# Practice Markdown
# Headings
# Heading 1 {#heading-1}
Use \# for headings 1 for heading 1, 2 for heading 2, and so on. 


## Heading 2
### Heading 3
#### Heading 4
##### Heading 5 (no need for this)

# Spaces in MD
Want to break to the next line?  
Insert **2** spaces at the end of the line  
and the line will break. If you do not do this 
nothing happens.

# Blocks of text
## Code Block
To insert a fenced codeblock with syntax highlighting:  

```json
{
  "first-name": "Laura",
  "last-name": "Novich",
  "years-in-tc": 20
  "years-in-ed": 12
}
```
## Block Quote
Use this to highlight an idea or phrase

Vincent Lombardi said:
>Perfection is not attainable,  
>but if we chase perfection  
>we can catch excellence.

# Footnotes
When you create a footnote, a superscript number with a link appears where you added the footnote reference. 
Readers can click the link to jump to the content of the footnote at the bottom of the page.  
To create a footnote reference, add a caret and an identifier inside brackets ([^1]). 
Identifiers can be numbers or words, but they can’t contain spaces or tabs. 
Identifiers only correlate the footnote reference with the footnote itself — in the output, footnotes are numbered sequentially.  
Add the footnote using another caret and number inside brackets with a colon and text ([^1]: My footnote.). 
You don’t have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.  

```Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
```

Here's a simple footnote,[^1] and here's a longer one.[^bignote]
[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

# Links    
``[alt-text](link)`` 

For example
[Link to Heading 1](heading-1)

    
    
