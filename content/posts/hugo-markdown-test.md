---
title: Hugo Markdown Test
date: 2025-08-18T22:08:20+02:00
publishdate: 2025-08-18
lastmod: 2025-08-18
author: Yuanhe
draft: false
tags:
  - Html
  - Markdown
categories: 
  - Tech
---
This post is for testing how to use different content formats with Markdown of Hugo.

## Font Styles
This is **bold** text, and this is *italic* text.   
This is ~strikeout~ text.  
This is <mark>highligh</mark> text.

More:   
Another <del>strikeout</del> text.   
This is <ins>underline</ins> text.   
Another <u>underline</u> text.   
Subscript: H<sub>2</sub>O is water.   
Superscript: 1<sup>st</sup> Place   

> To enable the highlight feature needs adding below settings to the config file `hugo.yml`:
```yaml
markup:
  goldmark:
    renderer:
      unsafe: true
```


## Link
Example: Visit the [Hugo](https://gohugo.io) website!


## Blockquotes
> Let's make a nested blockquote!
>> If you can't explain it to a six year old, you don't understand it yourself.   
>> {{< rtl >}} Albert Einstein --- {{< /rtl >}}

## Lists
### Ordered List
1. First item
2. Second item
3. Third item
4. Fourth item

### Unordered Lists
- First item
- Second item
- Third item
- Fourth item

## Code
### Inline code
At the command prompt, type `nano`.
### Code Blocks
Code (with syntax highlight):
```py
print("Hello, World!")

n = 10
for i in range(n):
    print(i)

print("Goodbye, World!")
```   
Output (plain):
```output
Hello, World!
0
1
2
3
4
5
6
7
8
9
Goodbye, World!
```


## Images
![Mandelbrot Set](/images/mand_v01.png "Mandelbrot Set")
![Totoro](/images/totoro.gif#center "Totoro")

## Emojis
:smile: :smiling_face_with_tear:   
:dog: :cat:   
:gb: :cn:
> *To display flag emojis in Windows needs [this Chrome Extention](https://chrome.google.com/webstore/detail/country-flag-fixer/jhcpefjbhmbkgjgipkhndplfbhdecijh). 
(source: [Flag emojis not showing : r/chrome](https://www.reddit.com/r/chrome/comments/kl3hym/flag_emojis_not_showing/))

# References
- [Basic Syntax | Markdown Guide](https://www.markdownguide.org/basic-syntax)
- [Hugo Quick reference - Emojis](https://gohugo.io/quick-reference/emojis/)

---
---

# Below shows the original markdown code of the article above:
---
<pre>
This post is for testing how to use different content formats with Markdown of Hugo.

## Font Styles
This is **bold** text, and this is *italic* text.   
This is ~strikeout~ text.  
This is &lt;mark>highligh&lt;/mark> text.

More:   
Another &lt;del>strikeout&lt;/del> text.   
This is &lt;ins>underline&lt;/ins> text.   
Another &lt;u>underline&lt;/u> text.   
Subscript: H&lt;sub>2&lt;/sub>O is water.   
Superscript: 1&lt;sup>st&lt;/sup> Place   

> To enable the highlight feature needs adding below settings to the config file `hugo.yml`:
```yaml
markup:
  goldmark:
    renderer:
      unsafe: true
```


## Link
Example: Visit the [Hugo](https://gohugo.io) website!


## Blockquotes
> Let's make a nested blockquote!
>> If you can't explain it to a six year old, you don't understand it yourself.   
>> {{&lt; rtl >}} Albert Einstein --- {{&lt; /rtl >}}

## Lists
### Ordered List
1. First item
2. Second item
3. Third item
4. Fourth item

### Unordered Lists
- First item
- Second item
- Third item
- Fourth item

## Code
### Inline code
At the command prompt, type `nano`.
### Code Blocks
Code (with syntax highlight):
```py
print("Hello, World!")

n = 10
for i in range(n):
    print(i)

print("Goodbye, World!")
```   
Output (plain):
```output
Hello, World!
0
1
2
3
4
5
6
7
8
9
Goodbye, World!
```


## Images
![Mandelbrot Set](/images/mand_v01.png "Mandelbrot Set")
![Totoro](/images/totoro.gif#center "Totoro")

## Emojis
:smile: :smiling_face_with_tear:   
:dog: :cat:   
:gb: :cn:
> *To display flag emojis in Windows needs [this Chrome Extention](https://chrome.google.com/webstore/detail/country-flag-fixer/jhcpefjbhmbkgjgipkhndplfbhdecijh).
(source: [Flag emojis not showing : r/chrome](https://www.reddit.com/r/chrome/comments/kl3hym/flag_emojis_not_showing/))

# References
- [Basic Syntax | Markdown Guide](https://www.markdownguide.org/basic-syntax)
- [Hugo Quick reference - Emojis](https://gohugo.io/quick-reference/emojis/)


</pre>
---
Here is the end of the markdown code.


# PS: 
> [How to display raw HTML code on an HTML page - Stack Overflow](https://stackoverflow.com/questions/2820453/how-to-display-raw-html-code-on-an-html-page)
>> 1. Replace the `&` character with `&amp;`
>> 2. Replace the `<` character with `&lt;`
>> 3. Replace the `>` character with `&gt;`
>> 4. Optionally surround your HTML sample with `<pre>` and/or `<code>` tags.
>  
> (For `<` and `>`, I only repalced the `<` symbols to make them unpaired.)

