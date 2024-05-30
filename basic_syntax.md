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
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/image.png)

3. Close the file.








