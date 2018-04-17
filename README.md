# Markdown: Doing fancy stuff in Discord text

You may have noticed some discord messages have fancy formatting. This is acomplished by using the markdown format. Discord only allows for a specific subset of the format right now. 

### Basics
*Italics* - `*Italics*`    
**Bold** - `**Bold**`    
~~Strikeout~~ - `~~StrikeOut~~`    
__Underline__ - `__Underline__`    

### Combos
***Bold Italics*** - `***Bold Italics***`    
__*Underline Italics*__ - `__*Underline Italics*__`    
__**Underline Bold**__ - `__**Underline Bold**__`    
__***Underline Bold Italics***__ - `__***Underline Bold Italics***__`

### Disabling Markdown
Discord also provides a way to prevent markdown from being applied, just add a backslash `\` before the markdown character. For example, `\**Not Bold**` will prevent the text from being bold, and the backslash will disapear from the visible text. In the case of combined formats, you may need multiple backslashes. Using the example with all three, you would need four backslashes to disable the markdown. `\__\*\*\*Not Underline Bold Italics***__`

### Quotes and Code

If you want to do some quoted text, surround the text in backticks \`.    
`This is quoted text`

If you want to do a multiline quote, surround the text in three backticks. \```    
```
This is a haiku 
about a wonderful thing 
called markdown Format.
```
