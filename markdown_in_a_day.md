# Table of Contents
- [Table of Contents](#table-of-contents)
- [1- Heading in markdown.](#1--heading-in-markdown)
- [2- Blocks of Text](#2--blocks-of-text)
- [3- Line Breaks](#3--line-breaks)
- [4- Combining Two Elements](#4--combining-two-elements)
- [5- Text Styling](#5--text-styling)
- [6 - Bullet Points / Lists in Markdown](#6---bullet-points--lists-in-markdown)
- [7- Creating a Line](#7--creating-a-line)
- [8- Links and Hyperlinks](#8--links-and-hyperlinks)
- [9 : Images and Figures with Link](#9--images-and-figures-with-link)
- [10- Writing Code Blocks in Markdown and Different Programming Languages](#10--writing-code-blocks-in-markdown-and-different-programming-languages)
- [11- Creating or Adding Table:](#11--creating-or-adding-table)
- [12- Create Content List](#12--create-content-list)
- [13- Useful Markdown Extensions](#13--useful-markdown-extensions)
- [14- Commenting out In Markdown:](#14--commenting-out-in-markdown)
- [15- Checkboxes In Markdown](#15--checkboxes-in-markdown)
- [16- Adding FootNote:](#16--adding-footnote)
- [17- Adding Emoji:](#17--adding-emoji)
- [18- Adding Alerts `Warning`, `Note` and `Bulb` Logo aka Admonitions:](#18--adding-alerts-warning-note-and-bulb-logo-aka-admonitions)



# 1- Heading in markdown.
In Markdown, there are six levels of headings, and you can create them by using hashtags (#) followed by a space. The number of hashtags determines the heading level, and the font size decreases as you add more hashtags. Here are the headings:
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# 2- Blocks of Text
In Markdown, a block of text means that everything you write is represented as a distinct block. Notion, a popular app, employs this method to structure text. Each line or entry in Notion constitutes a block of text.

Now, let's distinguish between "Blocks of Text" and "Plain Text" in Markdown. For "Plain Text," you start writing without any special symbols or codes, just like you would in a word processor. Markdown files (.md) naturally display plain text. In contrast, for "Blocks of Text," you use the ">" symbol, followed by your text, to create this distinctive block.

Here's an example of creating a "Block of Text" using the ">" symbol. There's no need for a space after the ">" symbol; you can start writing immediately:

 <!-- In markdown the code will continue as "Block of Code" untill you press the "ENTER keyboard key" twice --> 
> First example of writing a 'Block of Text': My name is Ali, and I'm learning the Markdown language. Markdown is a great language for people new to coding, as it boosts their enthusiasm.

> Second Example: If you want to increase the line spacing in Markdown, all you have to do is write another ">" symbol, press "Enter," and start writing again with another "Block of Text" symbol ">".
> 
> start writiing again with another  "Block_of_Words " symbol ">". Just like we did in this example.

> Third Example: If you want to create an empty space between two "Blocks of Text," simply double-press "Enter" from the keyboard, and then start writing your new "Block of Text."

> Just like this.

# 3- Line Breaks


Line breaks are important for separating paragraphs or indicating other divisions in your text. In Markdown, there are several methods to create line breaks.

The first and most straightforward method is to double-press the "Enter" key from your keyboard.

The second method involves using a backslash \ to end the paragraph and start a new line. However, this method is not always reliable and is not recommended.

The third method is widely used and recommended. You can use the <br> HTML line break tag to create a line break in your Markdown text. For example, you can write <br> to start a new line.

# 4- Combining Two Elements
In Markdown, combining two features is common and requires practice. For example, if you want to write something as a `heading` and also include a `block of text` along with it, you can do the following:

> All you need is:  `> # Write here`. The code will be written in a block of words and heading size will be there. As you can see below.

> # This is combination of two feature in markdown

# 5- Text Styling
How to style your text:
<br>"Bold"
<br> "Italic"
<br> "Bold and Italic
<br> " Strikethrough"

### Method 1: 
Using Asterisks * <br>

*Single Start in the start and in the end will Make the text Italic*

**Double Stars will make the text BOLD**

***Three stars in the start and end of the selected text will make teh text bold and italic together*** 
<!-- Remember There should be no spaces in between start and also text will start right after you apply start not like "Heading" where you need to give space after you write #--> 

#### Second method to use to make text italic, bold and both :

_Use the SINGLE underscore around the text without the space to make text italic_ <br>

__Use double underscore on both side of text together without space and the text will be bold__ <br><br>
___To make the text bold and italic together use the underscore three times all together without spaces.___

To make a line `strikethrough` use the double `tildes` on both side `~~` of the statement: e.g: 
~~I am enjoying learning Markdown~~



# 6 - Bullet Points / Lists in Markdown

- Day 1
- Day 2
- Day 3

>In Markdown to create a list without numbering a.ka unordered list you have to do following :
> You have to use "dash and a space" just like this "- " to create a bullet point in the MARKDOWN. ___A space after - (dash) is very important i.e - .___Otherwise the list will not be created___

### **Let's see how we can subbullets of a a bullet:**
To create sub-bullets, you can apply the same rules used for normal bullets and apply indentation.
> Example 1
- This is the first bullet.
  - This is 1st sub_bullet<!-- Single Indentation to parent bullet-->
    - This is 2nd sub_bullet .<!-- Single Indentation to sub_bullet-->
      - This is 3rd sub_bullet.

> Exmaple 2 for sub_bullet:
- This is a bullet.
  - This is another sub_bullet of a bullet.
  - This is another sub_bullet of a bullet point .
- Now we create a new bullet.

> To create a **Numbered List**, you use a number followed by a full stop and a space, such as "1. " or "33. ". The space is important, or it won't be turned into a list. The rules for sub-numbering are similar to sub-bullets.

1. This is number 1.
2. This is number 2
   1. This is 1st first sub number of Number 2.
   2. This is 2nd sub number of Number 2.
3. This is Number 3.

> You can also create lists or bullet points using two different symbols: "(+ ) plus with a space" and "(* ) single star with a space."

Example with "+":

+ This is how we create bullet using + space.
  + Also the sub_bullet using + space

* This is a way to create bullet using * and space.
  * This is a way to create sub_bullet using * space.
    * This is third tier of sub_bullet.


# 7- Creating a Line

We can create a line under something a full length line by three method

1. Press dash three time ---
2. Press underscore three times ___ .
3. Press asteric three times ***

First Example: Press dash three times ---

---

Second example: Press underscore three times ___ 
___

Third example: Press asteric three times ***
***


# 8- Links and Hyperlinks

To create a hyperlink in Markdown, you have several methods depending on your requirements and how you want to represent the hyperlink. Let's explore them step by step.

#### Method 1:  Simple Hyperlink :

The simplest way to insert a hyperlink in Markdown is to paste the URL directly. For example, if I want to post a hyperlink to my YouTube channel, I can simply provide the URL:


https://www.youtube.com/channel/UCZBHJ6x6tcwkOq21x4lfGqg/ .

#### Method 2: Creating a Hyperlink Text


n this method, you create a clickable text that directs to the desired website. To do this, you first create the text you want to display to your audience inside square brackets [], and then you insert the original hyperlink within parentheses ().
[This is Ali Talha YouTube Channel](https://www.youtube.com/channel/UCZBHJ6x6tcwkOq21x4lfGqg/)

This text will appear as a clickable link: This is Ali Talha's YouTube Channel

#### Method 3: Creating a Hyperlink with a Variable
This method is useful when you want to highlight specific text within a paragraph and link it to a particular URL. It allows you to create a kind of variable in Markdown that can be reused throughout your document.

The process for creating a variable in Markdown involves these steps:

1. Create a variable name enclosed in square brackets [].
2. Add a colon : immediately after the variable name.
3. Insert the original hyperlink within parentheses ().
For example, if you want to create a variable named "My Channel" that links to your YouTube channel:

> The format will look like this : [My Channel]: https://www.youtube.com/channel/UCZBHJ6x6tcwkOq21x4lfGqg/  

> Important : When you create a variable [My channel] and put colon :. There should be no space between them. Later after colon you can put a space and insert the prenthesis () and write URL in prenthesis

> Aftreward to call the variable in text . You put the text in [ ] and without space put the variable in another  [ ]

[Home Page]: (https://www.youtube.com/channel/UCZBHJ6x6tcwkOq21x4lfGqg/) 

Now if i want to use that variable into my text . I will say that , guys do like my channel by clicking [here][Home Page].

# 9 : Images and Figures with Link

In Markdown you cannot put your image directly from your own computer hard drive. Only ways are either host that image on web or either put that image in yuor IDE or Editor you are working on. Let's take a look one by one.

#### Method 1 :Inserting Image Using URL:

- First you have to find an image you want to show in the file . Copy the url. In this example we are using this URL image of "Markdown Logo " . URL is : https://miro.medium.com/v2/resize:fit:828/format:webp/1*eZ7YPTqzcyFVoQxIOIQ9kQ.png  .
- Now we will use the same process what we did in creating a hyperlink . [Name we want to display](the url address)
- But, to show image in our file we use exclamation mark on the start of the code "!". So it will look like this :

```Markdown
![name_to_display](the_url_address)

```

![This is Muhammad Ali Boxer](https://miro.medium.com/v2/resize:fit:828/format:webp/1*eZ7YPTqzcyFVoQxIOIQ9kQ.png)

#### Method 2 :Inserting Image using Editor (e.g VS code):
+ Download the image you want to include in your Markdown file and copy it into the same folder where you are creating the Markdown document.
+ Rename the image to whatever you like.
+ Use the exclamation mark ! to start the code, followed by the name you want to display in square brackets []. Then, inside parentheses (), write the image's filename, including the extension.

![Muhamamd Ali Boxer](Muhammad_Ali.jpg)

#### Method 2 : Reference Style for Image:
+ In this method you define the Reference for the image URL.
+ This method involves square brackets.
+ You have to create two set of square brackets side by side [][].
+ In first square bracket [] you write the `name to display`
+ In second bracket [] , you put a Reference name e.g `ref1`
+ After that at the bottom of your markdown file you put that Reference in this style [ref1]: the name of the url. 

![image][ref]



# 10- Writing Code Blocks in Markdown and Different Programming Languages
This is one of the most widely used methods in Markdown and is essential to learn. It allows you to include code blocks in your Markdown document and differentiate between different programming languages. Additionally, you can highlight a single line of code. Let's explore both methods step by step.

#### Method 1: Writing a single line code <br>
- To insert a single line of code in Markdown, you can use backticks. Place one backtick before the start of the code and one backtick after the code.
- The backtick can be found on the keyboard's upper numeric keys, typically on the extreme left side. `        `
- Let's see and example :

```python
print(This is an example of single line of code writting in python)
```

#### Method 2: Writing a Block of Code:

- To insert a block of code, you need to use three backticks at the start, press Enter, and then use three backticks at the end.

```
press enter and  three back ticks in the end .
```
- You write the code in between the three backtics.
- You can also specify the programming language name after first three backticks so it will show the same language coloring and output.

```
a = 5
b = 10
c = a + b
```

```Python
First_name  = 'Ali'
Last_name = 'Talha'
full_name = First_name + Last_name
# This block of code show that this code is written in python
```
These methods allow you to seamlessly integrate code into your Markdown document, making it a powerful tool for documenting and sharing code-related content.

# 11- Creating or Adding Table:
We can create tables in MARKDOWN using the symbol "PIPE" which is "|". 
- It is a good practice in creating or defining the table that we create headers first. 
- The syntax for writting the header in MARKDOWN is 
```Markdown
|Column_1 | Column_2|Column_3|  
|---------|---------|--------|
```
- The second line of code after you define , the column name is helpful to identify the column block in markdown so you can input data.
- Also, the second line of code is further use to align the data in left, right and middle of the column.
- To align the data in the left side you put colon on the left  in the second line of code which you created after the header
```Markdown
|Column_1 | Column_2|Column_3|
|:---------|:---------|:--------|
```
> the above block of code will align the data in column to the left

- To align the data in the "Right side" you put colon on the "Right"  in the second line of code which you created after the header 
```Markdown
|Column_1 | Column_2|Column_3|
|---------:|---------:|--------:|

```
> The above block of code will align the data in column to the Right
- To align the data in the "MIDDLE" you put colon on the "both sides"  in the second line of code which you created after the header 
```Markdown
|Column_1 | Column_2|Column_3|
|:---------:|:---------:|:--------:|

```
> the above block of code will align the data in column to the Right


|Column_1 | Column_2|Column_3|
|---------|---------|--------|
|Ali      |Talha    |Ali_Talha|
|Rizwan   | Ahmad    | Rizwan_Ahmad|
|Ali      |Talha      |Ali_Talha|
|Rizwan    | Ahmad    | Rizwan_Ahmad|
|Ali|Talha|Ali_Talha|
|Rizwan| Ahmad| Rizwan_Ahmad|
|_Ali_|Talha|Ali_Talha|
|Rizwan| Ahmad| Rizwan_Ahmad|
|Ali|Talha|Ali_Talha|
|Rizwan| Ahmad| Rizwan_Ahmad|
|Ali|Talha|Ali_Talha|
|Rizwan| Ahmad| Rizwan_Ahmad|

# 12- Create Content List
- This method allows you to create a clickable table of contents for your Markdown document, making it easy for readers to navigate to specific sections or headings.
- In order to create a content list so when you click on a link it will leads to the specfic heading or area.
This is more like a content of a book.
- To Create a Contect of your page. You follow the same rule as you created URL link. e.g [Name to Display](#22--The area where you want to go)

[Heading](#1--heading-in-markdown)\
[Block of Words](#2--block-of-words)\
[Line Breaks](#3--line-breaks)\
[Combine Two Things](#4--combine-two-things)\
[Face Of Text](#5--face-of-text)\
[Bullet Points and List Writting](#6---bullet-points--lists-writting-in-markdown)\
[Create A Line](#7--create-a-line)\
[Creating Link and Hyperlin](#8--links-and-hyperlink)\
[Inserting Images and Figures](#9--images-and-figures-with-link)\
[Creating Tables In Markdown](#10--creating-or-adding-table)\
[Create Content List](#11--create-content-list)\
[Extensions for Markdown](#12--extensions-for-markdown)

# 13- Useful Markdown Extensions

1. Markdown All In One [Website](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one).
2. Markdown Pdf [Website](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).
3. MarkdownLint [Website](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
4. Markdown Shortcuts[Website](https://marketplace.visualstudio.com/items?itemName=mdickin.markdown-shortcuts).
5. Markdown Preview Enhanced [Website](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced).
6. Markdown Footnotes[Website](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-footnotes)
7. Markdown Emoji [Website](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-emoji)


# 14- Commenting out In Markdown:

- Commenting out in Markdown involves adding comments to your document. Comments are lines of text that are not rendered in the output and are used for adding notes, explanations, or annotations within your Markdown file.

- Commenting out means marking certain lines of text or statements for reference, which will not be displayed in the output.
This feature is employed in almost all programming languages.
Markdown borrows the commenting out feature from HTML. To comment out a piece of text or a statement, you can use the following syntax:
  > `<!-- Your code or statment yo uwant to comment out will go here -->`
  


# 15- Checkboxes In Markdown
Creating a checklist or checkboxes is also possible in Markdown. To do so, you need to create a list first using `- ` teccnique which is also used to create bullet, as we learn [earlier](#11--create-content-list), then you need `square brakets`  which is represented by `[ ]` . with a s `space ` inside
> e.g `- [ ] i am ali`

- [ ] I am learning Python
- [ ] Markdown is fun. <br>

In order to place a check mark. Inside the square bracket you need to put > `x` inside the square brackets.

You can also created nedted checklist following the same [List](#11--create-content-list) method.

- [ ] List 1
- [ ] List 2
- [ ] List 3
  - [ ] List 5
  - [x] List 6

# 16- Adding FootNote:
Footnote is helpful if you are want to give Reference of some documnt in the footnote of your page.
In order to create footnote these are the steps :
1. Create a square brakets [ ]
2. Inside the square brackets you have to make a symbol of "Caret" i.e. `^`.  The keyboard shorcut is ` shift + 5`
3. After "Caret" Inside the square bracket write the number of the footnote as you desire . Could be 5,6,7 etc
4. Once you have created the footnote, then you have to go where you want to put the detail of that footnote and write the same number in square brackets with caret. Put colon `:` after that and write the Reference details. 

Here is a simple footnote[^5]
```Markdown
The sample to create a footnote . `How to create a footnote [^4]`
```

[ref]: https://d33wubrfki0l68.cloudfront.net/c919c1649f9bd8c95b2acf4b2d79bd8d03221068/c4b1c/static/img/blog/linting-markdown-files-with-markdownlint.jpg


[^5]: Foot Note Example

# 17- Adding Emoji:

Adding emoji in markdown is Possible. 
1. First you have to download the extension for that check list of all [Extensions Here](#12--extensions-for-markdown)
2. You need codes for the emoji, here is the [Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/) for emojis.
3. Copy the emoji code  from the website and paste in your markdown file 😋
4. Sometime you have to write the code betwee two colons e.g `:efdfdf:`



# 18- Adding Alerts `Warning`, `Note` and `Bulb` Logo aka Admonitions:
Just like whule reading a book you get some highlited text with a smal tiny logo representing why this highlited text is important. you can do the same as in Markdown.

1. In Markdown you can add three type of Alerts or they also called Admonitons.
2. The syntax is  create a block of code first usin `>`  
3. Create two colons `::` in between those  colon write `memo`, `warning` or `bulb`.
Markdown

Examples:

```Markdown
>:warning: Warning: Do not push the big red button.

>:memo: **Note:** Sunrises are beautiful.

>:bulb: **Tip:** Remember to appreciate the little things in life.

```
> :warning: Warning: Do not push the big red button.

>:memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.
