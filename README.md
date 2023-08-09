# Heading level 1 {#custom-id}

## Heading level 2 

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6 {#header-2}

_____________________________________________________

Alternate Syntax
================

Heading level 1
=

Heading level 2
---------------

Heading level 2
---

******************************************************

# Paragraphs

> `To create paragraphs, use a blank line to separate one or more lines of text.`

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

-------------------------------------------------------

# Line Breaks

> `To create a line break or new line (<br>), end a line with two or more spaces`

This is the first line.  
And this is the second line.

First line with the HTML tag after.<br>
And the next line.

-------------------------------------------------------

# Bold

I just love **bold text**.  
I just love __bold text__.  
Love**is**bold  
**I just love bold text.**

-------------------------------------------------------

# Italic

Italicized text is the *cat's meow*.  
Italicized text is the _cat's meow_.  
A*cat*meow  
*Italicized text is the cat's meow.*

-------------------------------------------------------

# Bold and Italic

This text is ***really important***.  
This text is ___really important___.  
This text is __*really important*__.  
This text is **_really important_**.  
This is really***very***important text.  
***This is reallyveryimportant text.***

_____________________________________________________

# Blockquotes

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable

> Dorothy followed her through many of the beautiful rooms in her castle.

> Dorothy followed her through many of 
>
> The Witch bade her clean the pots and kettles and sweep 

> Dorothy followed her through many of the 
>
>> The Witch bade her clean the pots and kettles

> a1
>> a2
>>
>>> a3
>>> a4
>>>> a5

>>>>> b
>>>
>>>> b
>>>
>>> b

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

_____________________________________________________

# Ordered Lists

> 1. First item
> 2. Second item
> 3. Third item
> 4. Fourth item

> 1. First item
> 1. Second item
> 1. Third item
> 1. Fourth item

> 1. First item
> 8. Second item
> 3. Third item
> 5. Fourth item

> 1. First item
> 2. Second item
> 3. Third item
>     1. Indented item
>     2. Indented item
> 4. Fourth item

_____________________________________________________

# Unordered Lists

> - Second item
> - First item
> - Third item
> - Fourth item

> * First item
> * Second item
> * Third item
> * Fourth item

> + First item
> + Second item
> + Third item
> + Fourth item

> - First item
> - Second item
> - Third item
>     - Indented item
>     - Indented item
> - Fourth item

> - 1968\. A great year!
> - I think 1969 was second best.

_____________________________________________________

# Adding Elements in Lists

> `add another element in a list , four spaces or one tab`

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item

    ![image](/assets/images/linux.jpg "image in a list, four spaces or one tab.")
  
    **paragraph** in a list, four spaces or one tab.

    > **blockquote** in a list, four spaces or one tab.

        Code blocks in a list, eight spaces or two tabs.
        <html>
          <head>
            <title>Test</title>
          </head>
        </html>

4. Fourth item

_____________________________________________________

# Code

At the command prompt, type `nano`.

`<h1>header</h1>`

`Use `code` in your Markdown file.`

``Use `code` in your Markdown file.``

```Use ``code`` in your Markdown file.```

```Use ``code`` in your Markdown file.```

_____________________________________________________

# Code Blocks

> `To create code blocks, every line at least four spaces or one tab. `
   
    <html>
      <head>
      </head>
    </html>

> `To create code blocks, (```) or (~~~) `

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

```c#
function test() {
  console.log("notice the blank line before this function?");
}
```

```sh
cd dillinger
npm i
node app
```

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

```c#
sh
console
markdown
json
javascript
css
html
php
java
go
ruby
c#
c++
c
python
```

~~~html
<html> 
   <head> 
   </head> 
</html>
~~~

_____________________________________________________

# Horizontal Rules

> `*** | --- | ___` 

***

---

___

# Links

http://www.example.com

[Duck Duck Go](https://duckduckgo.com).

[tilte](https://duckduckgo.com "The best search").

**[EFF](https://eff.org)**.

*[Markdown Guide](https://www.markdownguide.org)*.

[`code`](#code).

[link space](https://www.example.com/my%20great%20page)

[hobbit-hole-mapper-1][1]

[hobbit-hole-mapper-2][2]

[Markdown site][df1]

[John Gruber]

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles1"

[2]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles2"

[john gruber]: http://daringfireball.net

[df1]: http://daringfireball.net/projects/markdown/

## URLs and Email Addresses

<https://www.markdownguide.org>

<fake@example.com>

_____________________________________________________

# Images

![image](https://mdg.imgix.net/assets/images/shiprock.jpg?auto=format&fit=clip&q=40&w=1080)

![image](/assets/images/linux.jpg)

## Linking Images

[![image](/assets/images/linux.jpg)](https://www.markdownguide.org)

_____________________________________________________

# Escaping Characters

\* Without  
\< Without \>  
\# Without

_____________________________________________________

# HTML

This **word** is bold. This <em>word</em> is italic.

_____________________________________________________

# Tables

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

|        Syntax        | Description    |             Test Text |
| :------------------: | :------------- | --------------------: |
| Header \|  Paragraph | `Title` &#124; | **Here's this  more** |
|      Paragraph       | ***Text***     |            *And more* |

| Syntax    | Description                                  |
| --------- | -------------------------------------------- |
| Header    | Title                                        |
| Paragraph | First paragraph. <br><br>  Second paragraph. |

| Syntax | Description                                                  |
| ------ | ------------------------------------------------------------ |
| Header | Title                                                        |
| List   | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |

_____________________________________________________

# Strikethrough

~~link~~

~~The world is flat.~~ We now know that the world is round.

_____________________________________________________

# Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

_____________________________________________________

# Linking to Heading IDs

[custom-id](#custom-id)

[header-2](#header-2)

[Heading IDs](https://www.markdownguide.org/extended-syntax#heading-ids).

_____________________________________________________

# Definition Lists

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

_____________________________________________________

# Task Lists

- [x] Write the press release
- [x] Update the website
- [ ] Contact the media
- [ ] \(Optional) Open a followup issue
- [ ] https://github.com/L-Briand/ShadowLayout/issues/8
- [ ] https://github.com/lopspower/CircularImageView/issues/138
- [ ] https://github.com/lopspower/CircularImageView/pull/140

_____________________________________________________

# Emoji

✨✨✨🔥

:tent:

:joy:

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

_____________________________________________________

# Highlight

I need to highlight these ==very important words==.

I need to highlight these <mark>very important words</mark>.

_____________________________________________________

# Subscript

H~2~O

H<sub>2</sub>O

_____________________________________________________

# Superscript

X^2^

X<sup>2</sup>

_____________________________________________________

# Automatic URL Linking

http://www.example.com

`http://www.example.com`

_____________________________________________________

# Comments

> `[comment]: #`

[This is a comment that will be hidden.]: # 

[//]: # (These are reference links used in)

<!-- TO DO: add more details about me later -->

_____________________________________________________

# Alerts

> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

_____________________________________________________

# Image Captions

<img src="/assets/images/linux.jpg" width="200" height="100">

<figure>
    <img src="/assets/images/linux.jpg" alt="Albuquerque, New Mexico">
    <figcaption>A single track trail outside of Albuquerque, New Mexico.<figcaption>
</figure>

![Albuquerque, New Mexico](/assets/images/linux.jpg)
*A single track trail outside of Albuquerque, New Mexico.*

_____________________________________________________

# Symbols

Copyright (©) — &copy;  
Registered trademark (®) — &reg;  
Trademark (™) — &trade;  
Euro (€) — &euro;  
Left arrow (←) — &larr;  
Up arrow (↑) — &uarr;  
Right arrow (→) — &rarr;  
Down arrow (↓) — &darr;  
Degree (°) — &#176;  
Pi (π) — &#960;  

_____________________________________________________

# Table of Contents

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)

_____________________________________________________

# Videos

> `[![Image alt text](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE-ID)`

[![Less Than Jake](https://img.youtube.com/vi/PYCxct2e0zI/0.jpg)](https://www.youtube.com/watch?v=PYCxct2e0zI)

_____________________________________________________

# Mark

$\sqrt{3x-1}+(1+x)^2$

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```

$\sqrt{\$4}$

_____________________________________________________

# Color

 `#ffffff`

 `#000000`

 #ffffff

`#0969DA`

`rgb(9, 105, 218)`

`hsl(212, 92%, 45%)`

_____________________________________________________

# Not Support

&nbsp;&nbsp;&nbsp;&nbsp;**tag** is the first sentence of my indented paragraph.

<p style="text-align:center">**Center** this text</p>

<p style="color:blue">Make this text blue.</p>

Some of these words <ins>will be **underlined**</ins>.

<a href="https://www.markdownguide.org" target="_blank">Link Targets</a>

_____________________________________________________

# collapsed section

<details>
  <summary>Click to expand!</summary>

  ## heading
  1. one
  2. two
  3. three

| Rank | Languages  |
| ---: | ---------- |
|    1 | Javascript |
|    2 | Python     |
|    3 | SQL        |

</details>

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section. 

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>

_____________________________________________________

# Creating Mermaid diagrams

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

_____________________________________________________

![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)

![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

_____________________________________________________

# Footnotes note

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
