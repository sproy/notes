# *==Basic Practice* :smile:

## Sections
### level 3
#### level 4
#### level 4

## Emphasis
Write this **text** in markdown.

## Lists
unordered list items
* one item
four items
five items
* two items
* three items

ordered list items
1. one item
four items
five items
2. two items
3. three items

## Block Quotes
> This is a text that we want to put in block quotes.
> Your task is to do this.

## Links
Write a text and insert a [link](http://www.bing.com "bing") to a web page and to a [section](#Sections) in your text.
This will go to section [Emphasis](#Emphasis).
See my code block [with hashtag](#my-code)

## Images
Find an image file and insert it into a text.
![footer](Team meeting.assets/image-20200528133154467.png)

# *Pandoc Markdown Extensions*

## Lists
3. This lists start at 3.
5. Although we used "5.", it gets 4.

***This works using pandoc to render it***
(@) Starting a list
(@) Continuing the list
Here is some text that doesn't belong to the list.
(@) This continues the list
(@test) This item is labelled so that we can refer back to it at (@test)

***The definition seems not work yet***
Something we want to define
:   Definition of the thing.
    as long as there's indentation, it becomes part of the definition.

Term 1 
    ~ Definition 1
Term 2 
    ~ Definition 2a 
    ~ Definition 2b


## Tables

Right   Left
----    ----
12      12
123     123
1         1
    

## Footnotes

Footnote inside a paragraph.^[This is the footnote.]

Reference to a footnote.[^footnotelabel]

[^footnotelabel]: This is footnote two.
If you want it to cover multiple lines, you 
have to indent the following footnote lines. 
by at least four spaces.


## Code Block

Both ` and ~ are used to identify a code block

```{.python #my-code .numberLines startFrom=100 .lineAnchors}
def func():
    print('hello world')
```

~~~{.python .numberLines}
def func():
    print('hello world')
~~~