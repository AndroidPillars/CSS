# CSS

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

# Inline CSS: 

- Directly in the html element.
- It's not the recommended way.
```ruby
<body style= "background-color: blue;">
```

# Internal CSS:

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
      
 # External CSS:
 
 - Similar to Internal CSS but have to seperate by linking an external.css file.
 
 __In index.html,__
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

 # CSS Syntax:
 
 selector { property : value; }
 
 selector -> who, property -> what, value -> How
 
 # CSS Selectors:
 
 Example:
 
   - img class="background1" src="images/android.png" alt="Image Not Loading"
   
  .background1{
   background-color: blue;
      }
      
 # ID Selectors:
 
 Example:
 
  - img id="background1" src="images/android.png" alt="Image Not Loading"
   
  #background1{
   background-color: blue;
      }
      
 # Pseudo Class:
 
 Example:
 
  - img:hover{
    background-color: blue;
    }
 
 
 Installation: chrome webstore -> Search Pesticides -> add to extensions -> Pesticides extension -> Allow Access to file URLs

keywords For Search: border-style css mdn, css default values, devdocs.io/css/height, mdn -> https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#Keyword_index

 
 # Tools Reference
 
 - colorhunt.co (For Color picker)
 - https://emojipedia.org/ (for emoji icons based on platform)  
  
 


