# Sigmapedia
The official unofficial wiki for the 100% totally real religion of Sigmism.

## Contributing
Thanks for contributing to the Sigmapedia! Let's turn some Ls into Ws here.
 - If you need help ask me. I need to add you to the repository to give you editing access first. Make a fork and pull request if you cannot wait.
 - Use GitHub (or just plain git, but I know you're not all programmers) to *commit* your changes.
   - Unless it is a small change always commit to a new branch. Create a new one with your name or something, do the edits in that branch, and then make a pull request, to merge it into the main one one we review it. Then, every once in a while, main will be merged into the prod (production) branch which is put onto the website
 - The articles can be found in the docs folder. They are Markdown, ending in .md (see guide below)
 - Don't edit the other files unless you know what you're doing
 - If you're feeling adventurous, install Python and the mkdocs and material-mkdocs pip packages, then cd into the root project folder and type `mkdocs serve`, then you can preview the wiki at the address it gives. Press ^c to stop.
 - yea that's it ask me if you need anything

## Editing
Here, everything is in markdown. Markdown is easy, you probably use it every day without realising. Discord messages are just a stripped down version of markdown. It's just text.

# Markdown syntax guide

It's pretty simple. You can type text and it just works normally. If you want to get fancy you can include the stuff below. If you have problems, tell me and I'll deal with them...

```

## Headers

# This is a Heading h1
## This is a Heading h2
###### This is a Heading h6

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered
(Put a space before and after the *, - works too instead of *)
* Item 1
* Item 2
* Item 2a
* Item 2b

### Ordered

1. Item 1
2. Item 2
3. Item 3
    1. Item 3a
    2. Item 3b

 - Indent lists with
    - tabs or 4 spaces

## Images

![They're links, but to the file and with a ! before them. This is a description of the image, appearing when the image can't be loaded.](./docs/assets/sigma.png)

## Links

Links go inside [square brackets for the text and the url in normal parentheses after, with no space in between](https://sigmism.surge.sh/).

## Blockquotes

> "As I drank, I felt a surge of power and freedom that I had never known before. In that moment, I became Baby Gronk, Skibidi’s loyal disciple."
>> You can also indent blockquotes with two blocks.

## Tables

| Left columns  | Right columns |
| ------------- | --------------|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

## Blocks of code or unformatted text

\```
let message = 'Hello world! Surround multiline blocks of code with ```s';
alert(message);
\```

## Inline code

Surrounded with one backtick for `code like this`.
```

Now let's see what that text looks like in markdown:

## Headers

# This is a Heading h1
## This is a Heading h2
###### This is a Heading h6

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered
(Put a space before and after the *, - works too instead of *)
* Item 1
* Item 2
* Item 2a
* Item 2b

### Ordered

1. Item 1
2. Item 2
3. Item 3
    1. Item 3a
    2. Item 3b

 - Indent lists with
    - tabs or 4 spaces

## Images

![This is a description of the image, appearing when the image can't be loaded.](./docs/assets/sigma.png)

## Links

Links go inside [square brackets for the text and the url in normal parentheses after, with no space in between](https://sigmism.surge.sh/).

## Blockquotes

> "As I drank, I felt a surge of power and freedom that I had never known before. In that moment, I became Baby Gronk, Skibidi’s loyal disciple."
>> You can also indent blockquotes with two blocks.

## Tables

| Left columns  | Right columns |
| ------------- | --------------|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

## Blocks of code or unformatted text

```
let message = 'Hello world! Surround multiline blocks of code with ```s';
alert(message);
```

## Inline code

Surrounded with one backtick for `code like this`.


