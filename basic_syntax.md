# Overview
Nearly all Markdown applications support the basic syntax outlined in the original Markdown design document. There are minor variations and discrepancies between Markdown processors — those are noted inline wherever possible.

# Headings

Example:
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

# Heading IDs
Many Markdown processors support custom IDs for headings — some Markdown processors automatically add them. Adding custom IDs allows you to link directly to headings and modify them with CSS. To add a custom heading ID, enclose the custom ID in curly braces on the same line as the heading.

### My Great Heading {#custom-id}


# Highlight
This isn’t common, but some Markdown processors allow you to highlight text. The result looks like this. To highlight words, use two equal signs (==) before and after the words.

    I need to highlight these ==very important words==.
The rendered output looks like this:
I need to highlight these ==very important words==.


# Subscript
This isn’t common, but some Markdown processors allow you to use subscript to position one or more characters slightly below the normal line of type. To create a subscript, use one tilde symbol (~) before and after the characters.

    H~2~O
The rendered output looks like this:
H~2~O


# Superscript
This isn’t common, but some Markdown processors allow you to use superscript to position one or more characters slightly above the normal line of type. To create a superscript, use one caret symbol (^) before and after the characters.

    X^2^
The rendered output looks like this:
X^2^


# Paragraphs
I really like using Markdown.

Example:
I think I'll use it to format all of my documents from now on.

# Line Breaks

Example:
This is the first line.  
And this is the second line.

# Emphasis
## Bold
To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

Example:
I just love **bold text**.
I just love __bold text__.
Love**is**bold

## Italic
To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

Example:
Italicized text is the *cat's meow*.
Italicized text is the _cat's meow_.
A*cat*meow

## Bold and Italic
To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

Example:
This text is ***really important***.
This text is ___really important___.
This text is __*really important*__.
This text is **_really important_**.
This is really***very***important text.

# Blockquotes
To create a blockquote, add a > in front of a paragraph.

Example:
> Dorothy followed her through many of the beautiful rooms in her castle.

## Blockquotes with Multiple Paragraphs
Blockquotes can contain multiple paragraphs. Add a > on the blank lines between the paragraphs.

Example:
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Nested Blockquotes
Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.

Example:
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Blockquotes with Other Elements
Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you’ll need to experiment to see which ones work.
Example:
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

# Lists
You can organize items into ordered and unordered lists.

## Ordered Lists
To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

### Ordered Lists var 1
Example:
1. First item
2. Second item
3. Third item
4. Fourth item

### Ordered Lists var 2
Example:
1. First item
1. Second item
1. Third item
1. Fourth item

### Ordered Lists var 3
Example:
1. First item
8. Second item
3. Third item
5. Fourth item

### Ordered Lists var 4
Example:
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## Unordered Lists
To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

### Unordered Lists var 1
Example:
- First item
- Second item
- Third item
- Fourth item

### Unordered Lists var 2
Example:
* First item
* Second item
* Third item
* Fourth item

### Unordered Lists var 3
Example:
+ First item
+ Second item
+ Third item
+ Fourth item

### Unordered Lists var 4
Example:
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## Starting Unordered List Items With Numbers
If you need to start an unordered list item with a number followed by a period, you can use a backslash (\) to escape the period.

Example:
- 1968\. A great year!
- I think 1969 was second best.

## Adding Elements in Lists

### Paragraphs

Example:
* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

### Blockquotes

Example:
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.


### Code Blocks
Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

Example:
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.



### Images

Example:
1. Open the file containing the image.
2. Security at its beauty.

    ![Security at its beauty](/assets/images/image.png)

3. Close the file.


### Lists
You can nest an unordered list in an ordered list, or vice versa.

Example:
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item




# Code
To denote a word or phrase as code, enclose it in backticks (`).

Example:
At the command prompt, type `nano`.

## Escaping Backticks
If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (``).

Example:
``Use `code` in your Markdown file.``


## Code Blocks
To create code blocks, indent every line of the block by at least four spaces or one tab.

Example:

    <html>
      <head>
      </head>
    </html>


# Horizontal Rules
To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

Example:
```
***
---
_________________
```

Render: 
***
---
_________________



# Links
To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

Example:
My favorite search engine is [Yandex](https://yandex.ru).


## Adding Titles
You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in quotation marks after the URL.

``` My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").```

The rendered output looks like this:
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## URLs and Email Addresses
To quickly turn a URL or email address into a link, enclose it in angle brackets.
```
<https://www.markdownguide.org>
<fake@example.com>
```

The rendered output looks like this:
<https://www.markdownguide.org>
<fake@example.com>


## Formatting Links
To emphasize links, add asterisks before and after the brackets and parentheses. To denote links as code, add backticks in the brackets.
```
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
```

The rendered output looks like this:
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).



# Images
To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.
```
![The Security is beautiful!](/assets/images/image.png "Security")
```

The rendered output looks like this:
![The Security is beautiful!](/assets/images/image.png "Security")

# Linking Images
To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.
```
[![The Security is beautiful!](/assets/images/image.png "Security")](https://www.cisecurity.org/cis-benchmarks)
```

The rendered output looks like this:
[![The Security is beautiful!](/assets/images/image.png "Security")](https://www.cisecurity.org/cis-benchmarks)



# Escaping Characters
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.
```
\* Without the backslash, this would be a bullet in an unordered list.
```

The rendered output looks like this:
\* Without the backslash, this would be a bullet in an unordered list.


# Tables
To add a table, use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. For compatibility, you should also add a pipe on either end of the row. Cell widths can vary, as shown below. The rendered output will look the same.

```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```
The rendered output looks like this:
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Alignment in tables
You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.
```
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```

The rendered output looks like this:
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## Formatting Text in Tables
You can format the text within tables. For example, you can add links, code (words or phrases in backticks (`) only, not code blocks), and emphasis.

**You can’t** use headings, blockquotes, lists, horizontal rules, images, or most HTML tags.


# Fenced Code Blocks
The basic Markdown syntax allows you to create code blocks by indenting lines by four spaces or one tab. If you find that inconvenient, try using fenced code blocks. Depending on your Markdown processor or editor, you’ll use three backticks or three tildes (~~~) on the lines before and after the code block. The best part? You don’t have to indent any lines!
    ```
    {
      "firstName": "John",
      "lastName": "Smith",
      "age": 25
    }
    ```
The rendered output looks like this:

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

# Syntax Highlighting
Many Markdown processors support syntax highlighting for fenced code blocks. This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, specify a language next to the backticks before the fenced code block.

    ```json
    {
      "firstName": "John",
      "lastName": "Smith",
      "age": 25
    }
    ```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

# Footnotes
Footnotes allow you to add notes and references without cluttering the body of the document. When you create a footnote, a superscript number with a link appears where you added the footnote reference. Readers can click the link to jump to the content of the footnote at the bottom of the page.

To create a footnote reference, add a caret and an identifier inside brackets ([^1]). Identifiers can be numbers or words, but they can’t contain spaces or tabs. Identifiers only correlate the footnote reference with the footnote itself — in the output, footnotes are numbered sequentially.

Add the footnote using another caret and number inside brackets with a colon and text ([^1]: My footnote.). You don’t have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.





