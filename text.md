# 1. Headings and comments
How to give hadings in markdown fies?
# Heading 1
## Heading 2
### Heading 3
For comments press shift alt A or ctrl forward slash / and write your comment like below
<!-- Comment -->
<!-- comment -->
# 2. Block of Words
this is a normal text
> This is a special text. you can make special text by putting greater than sign

> this is also special text
> if you want to merge these lines you can do by not giving double enter press for new line

# 3. Line Breaks
you can give line breaks by simply writing forwardslash symbol like this but right noww its not working you can also do it entering double times

hello new line
# 4. Combine two things
combining blocks of words and heading.

To do so use greater than sign and also use '#' for this purpose
> ## Block of heading

# 5. Face of Text
face of text includes bold text italic text and both also

for bold text simple write text in double asterik like this.

**Bold** Text

*Italic* Text

***Bold and Italic*** text

Or we can use these symbols like

For __Bold__ text use underscore two times

For _Italic_ text use underscore 1 time

For ___Bold and Italic___ use underscores 3 times.

# 6. Bullet Points
- Day 1
- Day 2
- Day-3
    - I have pressed tab for this sub bullet
- Day-4
 
 For numberings 

 1. Number 1
 2. Number 2
 3. Number 3
    1. Again pressed tab

We can also do it using asterik and plus symbol

+  one 
* Two

# 7. Line breaks and page breaks

To create a line use either 3 asteriks or 3 dashes or 3 underscores like below

---
***
___

Also if you want to increase the size of the texts then put dashes 1 2 or 3 immediately in newline after writing text like this 
-

# 8. Hyperlinks and Links 
to write hyperlinks paste your link in the angular braces <>.

For suchs links like click here to watch video then write word link in square brackets and place the link after closing bracket without space like this 

---

<https://www.youtube.com>

[To see the playlist Click me](www.myplaylist.com)

We can also store links in a key and use it in the later sections like 

[Codanics]:https://www.youtube.com
Codanics is now storing link of youtube

How to use this key?
To watch videos on youtbe Click [here][Codanics]
This codanic key is working fine
# 9. Images and figures with links
The way to do it is same as hyperlink just write exclamation mark before the hyperlink

To join please scan this pic
-

![pic](p1.jpg)
IF we dont put ! before hyperlink method then it will generqate the like like above links section like if we want to show give any pdf link then we will do it by skipping ! mark (Previous links method).
This pic should be present in the same folder where markdown file is present.

To show online pictures simply place the link of pic from google instead of pic path.
[codanic_pic](https://www.google.com/search?q=codanics&rlz=1C1CHBD_enPK971PK971&sxsrf=ALiCzsb0RnTTuC5kInTBXMm_h-nnTKzd-Q:1660830102002&source=lnms&tbm=isch&sa=X&ved=2ahUKEwiu3ouiwtD5AhXfXvEDHTE8DmMQ_AUoAXoECAEQAw&biw=960&bih=932&dpr=1#imgrc=GRjVtCcWAILqOM)
 This link will redirect to google pic.
To show here put exclamation before opening braces

# 10. Adding Code or code blocks
If you want to write code in between text then use this way
To print a string use ` print("Codanics") `

If you want to create a complete block of code then write 3 times ``` ``` and place your code
```
x = 5
y = 6
print("Sum is : ", x+y) 

```
We can also apply colors of any specific language to so just write language name after starting ``` and you will se colors like

> Python syntax
```python
x = 5
y = 6
print("Sum is : ", x+y) 

```
>R syntax
```r
x = 5
y = 6
print("Sum is : ", x+y) 

```
>Javascript syntax
```javascript
x = 5
y = 6
print("Sum is : ", x+y) 

```
# 11. Adding Tables

| Species | petal_length | sepal_length |
| :-------: | :---------: | :---------: |
| verginica | 18.2     | 19.2 |
| setosa | 12.2 | 13.4
| versicolor | 11.1 | 21.2
| setosa | 12.2 | 13.4
| versicolor | 11.1 | 21.2
| setosa | 12.2 | 13.4
| versicolor | 11.1 | 21.2
| setosa | 12.2 | 13.4
| versicolor | 11.1 | 21.2

<!-- We put colons on both starting and ending because to make it center align. if you want to make it left align then simply put colon on the left side and if you want to make it right align then put color on right side. -->
# 12. Table of Contents
[1- Headings and Comments](#1-headings-and-comments)\
[2- Blocks of words](#2-block-of-words)\
[3- Line Breaks](#3-line-breaks)\
[4- Combining two things](#4-combine-two-things)\
[5- Text Face](#5-face-of-text)\
[6- Bullet Points](#6-bullet-points)\
[7- Page Breaks](#7-line-breaks-and-page-breaks)\
[8- Hyperlinks](#8-hyperlinks-and-links)\
[9- Images and figures](#9-images-and-figures-with-links)\
[10- Code Blocks](#10-adding-code-or-code-blocks)\
[11- Table Creation](#11-adding-tables)\
[12- Colors in Markdown](#14-how-to-add-colors-in-markdown-language)\
[13- Mathematical Equations in Markdown](#15-how-to-write-mathematical-equations)

# 13. Install Extensions
extensions help in writing these markdown files


# 14. How to add colors in markdown language

> Colors in text
> -
<span style="color:green">
"To add colors in the text use span and set style to color and place your text in inverted commas like below."

"Jb tk close nhi kro gy tb tk green rhyga"
<!-- <span style="color:yellow">\
"Ab ye yellow ho gya he"
You can also put hexacode in place of color name (yellow and green) search on google hexcode color picker and pick your color code and put here and enjoy folks!.
</span> -->
</span>
Ab ye normal ho gya he.

# 15. How to write Mathematical Equations

>Inline Equation

$This_{is}^{Inline}$
>Maths Equation
$$ 
\int_0^\infty \frac{x^3}{e^x-1}\,dx=\frac{\pi^4}{15}
$$

for more practice you can visit MathJax github repo or MyST markdown overview. 
