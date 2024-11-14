# Uvod u markdown
## Create sophisticated formatting for your prose and code on GitHub with simple syntax.

### Headings
To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.
```
# A first-level heading
## A second-level heading
### A third-level heading
```
![Heading](assets/images/headings-rendered.webp)

When you use two or more headings, GitHub automatically generates a table of contents that you can access by clicking within the file header. Each heading title is listed in the table of contents and you can click a title to navigate to the selected section.

[Naslovne_razine](assets/images/headings-toc.webp)

## Styling text

You can indicate emphasis with bold, italic, strikethrough, subscript, or superscript text in comment fields and .md files.

## Quoting text

You can quote text with a >.
```
Text that is not a quote

> Text that is a quote
```
Quoted text is indented, with a different type color.

[quote_tekst](https://docs.github.com/assets/cb-13462/mw-1440/images/help/writing/quoted-text-rendered.webp)

## Quoting code

You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press the Command+E (Mac) or Ctrl+E (Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown.

```
Use `git status` to list all new or modified files that haven't yet been committed.
```
Use `git status` to list all new or modified files that haven't yet been committed.

To format code or text into its own distinct block, use triple backticks.
```
Some basic Git commands are:
```
git status
git add
git commit
```
```
[gitcomments](https://docs.github.com/assets/cb-34231/mw-1440/images/help/writing/code-block-rendered.webp)

For more information, see ["Creating and highlighting code blocks"](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)

If you are frequently editing code snippets and tables, you may benefit from enabling a fixed-width font in all comment fields on GitHub. For more information, see ["About writing and formatting on GitHub."](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github#enabling-fixed-width-fonts-in-the-editor)

## Supported color models

In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

```
The background color is `#ffffff` for light mode and `#000000` for dark mode.
```
[boje](https://docs.github.com/assets/cb-11643/mw-1440/images/help/writing/supported-color-models-rendered.webp)
