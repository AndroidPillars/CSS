# CSS

# HTML Drawbacks

- In order to display image and text side by side we have to use tables.
- We have to write lot of code to do that simple thing.
- Also, it is very easy to make syntax errors.
- To Overcome this, they introduced Cascading Style Sheets (CSS).

# CSS 

- Cascading Style Sheet
- This is called a style sheet or a style language in the sense that it can't do anything by itself.
- It's only purpose in life is to style markup language.
- Types: Inline CSS, Internal CSS and  External CSS.

```ruby
<body style= "background-color: blue;">
```

# Inline CSS: 

Format: body style="background-color: #ff6666;"

# Internal CSS:

Format: 

- style

      body{
        background-color: #ff6666;
      }

      hr{
        /* background-color: white; */
        /* border-style: dotted none none; */
        border-style: none;
        border-top-style: dotted;
        border-color:grey;
        border-width: 5px;
        height: 0px;
        width: 5%;
      }
      
 # External CSS:
 
 Similar to Internal CSS but have to seperate the file.
 
 - link rel="stylesheet" href="css/styles.css"
 
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

 
 Referrence: colorhunt.co (For Color picker), https://emojipedia.org/ (for emoji icons based on platform)  
  
 


