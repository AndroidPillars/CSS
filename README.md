# Topics

| S.No | Content |
| --------	 | ------------ |
| 1 | [HTML Drawbacks](README.md#html-drawbacks) |
| 2 | [CSS](README.md#css-1) |
| 3 | [Web Browser](README.md#web-browser) |
| 4 | [Text Editor](README.md#text-editor) |
| 5 | [IDE](README.md#ide) |
| 6 | [Inline CSS](README.md#inline-css) |
| 7 | [Internal CSS](README.md#internal-css) |
| 8 | [External CSS](README.md#external-css) |
| 9 | [CSS Selectors](README.md#css-selectors) |
| 10 | [Colors In CSS](README.md#colors-in-css) |
| 11 | [class attribute](README.md#class-attribute) |
| 12 | [id attribute](README.md#id-attribute) |
| 13 | [class vs id](README.md#class-vs-id) |
| 14 | [Pseudo class](README.md#pseudo-class) |
| 15 | [Pseudo element](README.md#pseudo-element) |
| 16 | [Favicons](README.md#favicons) |


# HTML Drawbacks

- In order to display image and text side by side we have to use tables.
- We have to write lot of code to do that simple thing.
- Also, it is very easy to make syntax errors.
- To Overcome this, they introduced Cascading Style Sheets (CSS).

# CSS 

- Cascading Style Sheet
- It is not a programming language.
- This is called a style sheet or a style language in the sense that it can't do anything by itself.
- It's only purpose in life is to style markup language.
- It is used for website layout and design.
- Can be extended with Sass/Less.
- Types: Inline CSS, Internal CSS and  External CSS.

# Web Browser

- Web Browser is used to view the HTML.
- Google Chrome
- Mozilla Firefox
- Safari
- Edge
- IE(Please Don't use this)

# Text Editor

- Text Editor is used to write the HTML.
- Sublime Text
- Atom.io
- Visual Studio Code
- Brackets
- Notepad++(Windows)
- TextMate(Mac)

# IDE

- Codepen.io
- atom.io
- https://code.visualstudio.com/

# Inline CSS  

- Directly in the html element.
- It's not the recommended way.
```ruby
<body style= "background-color: blue;">
```

# Internal CSS  

- Using ```<style>``` tags with in a single document.

```ruby
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Home Page</title>
    <style>
        body {
            background-color: blue;
        }
    </style>
</head>

<body>
    <h1>Hello World!!!</h1>

</body>

</html>
```
      
 # External CSS  
 
 - Similar to Internal CSS but have to seperate by linking an external.css file.
 
 __In index.html__
 ```ruby
 <!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Home Page</title>
    <link rel="stylesheet" href="css/styles.css">
</head>

<body>
    <h1>Hello World!!!</h1>

</body>

</html>
```
- Create a folder css and add a file name with style.css

__In style.css__
```ruby
body {
    background-color: blue;
}
```

 # CSS Selectors

```ruby
a { background-color: yellow; }
```
__where,__
- ```a```-> Selector
- ```{``` -> declaration start
- ```background-color``` -> property
- ```:``` -> Property/Value Seperator
- ```yellow``` -> Value
- ```;``` -> Declaration seperator
- ```}``` -> Declaration end

# Colors In CSS

- Color Names

```ruby
body {
    background-color: blue;
}
```
- HTML5 Color Names

```ruby
body {
    background-color: honeydew
}
```
- Hexa decimal

```ruby
body {
    background-color: #00ff00;
}
```
- RGB

```ruby
body {
    background-color: rgb(0,0,255);
}
```

# class attribute

- The Class attribute allows us to differentiate all of our different HTML elements.

__In index.html__

```ruby
<h1 class="heading1">HTML</h1>
<h1 class="heading2">CSS</h1>
```

__In style.css__
```ruby
.heading1{
    color: lawngreen;
}

.heading2{
    color: rgb(61, 99, 24);
}
```

# id attribute

- The id attribute specifies a unique id for an HTML element (the value must be unique within the HTML document).

__In index.html__

```ruby
<h1 id="heading1">HTML</h1>
<h1 id="heading2">CSS</h1>
```

__In style.css__
```ruby
#heading1{
    color: lawngreen;
}

#heading2{
    color: rgb(61, 99, 24);
}
```

# class vs id 

- use class when you want to apply the same style to a group of related items.
- In class, We can also use two classes to the same HTML element.

__In index.html__

```ruby
<h1 class="heading1 heading1bg">HTML</h1>
```
__In style.css__

```ruby
.heading1{
    color: lawngreen;
}

.heading1bg{
    background-color: lightcoral;
}
```
- use id  when you want to apply the specific style to a single element on your page.
- In id, We cannot use two id to the same HTML element.

# Pseudo class

- A pseudo-class is used to define a special state of an element.

```ruby
selector:pseudo-class {
  property:value;
}
```

__In index.html__

```ruby
<h1 class="heading1 heading1bg">HTML</h1>
```

__In styles.css__

```ruby
h1:hover{
    color: lightcoral;
}
```

# Pseudo element

- pseudo-element is used to style specified parts of an element

__In index.html__

```ruby
<p>
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam placeat,
 quasi molestias nobis voluptate temporibus officiis dicta, quas dolorem
 ducimus non laboriosam. Eius, perspiciatis aliquid. Facilis maiores
 ullam accusamus quasi.
</p>
```

__In styles.css__

```ruby
p::first-line {
    color: #ff0000;
    font-variant: small-caps;
  }
```

# Favicons

- A favicon (pronounced "fav-icon") is a small, iconic image that represents your website. 
- Favicons are most often found in the address bar of your web browser, but they can also be used in lists of bookmarks in web browsers and feed aggregators.
- Recommened format type -> ICO format which supports all types of browsers.

```ruby
<link rel="icon" href="favicon.ico">
```

```ruby
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="css/styles.css" />
    <link rel="icon" href="favicon.ico">
  </head>
  <body>
    <div>
      <h1 class="heading1 heading1bg">HTML</h1>
    </div>
  </body>
</html>
```

# Box Model

![box_model](https://user-images.githubusercontent.com/48873155/76243744-d2b8dd80-625e-11ea-82fa-9a33d0eef32e.png)

# Some Shorthand Properties

# Margin

```ruby
P{
    margin-top: 5px;
    margin-right: 10px;
    margin-bottom: 5px;
    margin-left: 10px;
}
```
```ruby
P{
    margin: 5px 10px 5px 10px; /* top, right, bottom, left */
}
```
```ruby
P{
    margin: 5px 10px; /* top + bottom, right + left  */
}
```
```ruby
P{
    margin: 5px 20px 10px; /* top, right + left, bottom   */
}
```

# font

```ruby
body {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
    font-weight: normal;
}
```
# Border

```ruby
.box{
    border-right: 5px maroon solid;
    border-left: 5px maroon solid;
    border-top: 5px  maroon solid;
    border-bottom: 5px  maroon solid;
}
```
```ruby
.box{
    border: 5px maroon solid;
}
```

# Reset

- It makes the default padding and margin to 0.

```ruby
*{
    margin: 0;
    padding: 0;
}
```

# div

- The div is a special element that allows us to divide our content up on our website so that we can structure each div seperately.
- In other words, The div stands for content division element and it basically allows you to split up or boxes so that you can affect the layout of each box seperately.
```ruby
<div>
 <h1>Android</h1>
 <p>Android was developed by Google</p>
</div>
```

# Display Property

- Block
- Inline
- Inline-Block
- None

# Common Block Elements

- Paragraph
- Headers
- Divisions
- Lists and List Items
- Forms

# Common Inline Elements

- Spans
- Images
- Anchors

- We cannot set the width for Inline elements

# Inline Block
# none

# CSS Static and Relative positioning

# Position
- Static
- Relative
- Absolute
- Fixed


Remember -> border -> solid
span in HTML


keywords For Search: border-style css mdn, css default values, devdocs.io/css/height, mdn -> https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#Keyword_index

# Plugins

- HTML Boilerplate
- Prettier
- Material Icon Theme

# Documentation References

- https://www.w3schools.com/css/
- https://developer.mozilla.org/en-US/docs/Web/CSS
- https://docs.emmet.io/cheat-sheet/
- https://devdocs.io/css/
 
 # Tools Reference
 
 - colorhunt.co (For Color picker)
 - https://emojipedia.org/ (for emoji icons based on platform)
 - https://www.favicon.cc/ (for generating fav.icon)
 - http://pesticide.io/ -> Installation -> chrome webstore -> Search Pesticides -> add to extensions -> Pesticides extension -> Allow  Access to file URLs
