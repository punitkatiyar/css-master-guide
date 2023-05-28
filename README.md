# CSS Master Guide


## 🧑🏼‍💻 CSS Core Module For Development <span style='font-size:40px;'>🥇</span>

**CSS stands for Cascading Style Sheets, and it is a language used to describe the presentation of HTML (Hypertext Markup Language) and XML (Extensible Markup Language) documents. CSS is used to control the layout, fonts, colors, and other visual aspects of web pages and user interfaces.**

## CSS provides several methods to define the styles. 

> Inline Styles

> Internal Style Sheets

> External Style Sheets

<hr>

## Inline Styles: 

**This method allows you to apply styles directly to an HTML element using the style attribute. This method is useful for making quick, one-off style changes.**

```
<h1 style="color: red;">This heading containt red color</h1>
```
<hr>

## Internal Style Sheets: 

**This method allows you to define the styles within the <head> section of your HTML document, using the <style> tag. This method is useful when you want to apply styles to a specific page only.**

```
<head>
  <style>
    h1 {
      color: red;
    }
  </style>
</head>
```
<hr>

## External Style Sheets: 

**In this method, you can define the styles in a separate CSS file, which is then linked to your HTML document using the <link> tag. This method allows you to maintain consistent styles across multiple pages.**

```
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>

```


### CSS File Code Like

```
/* Element Selector */
h1 {
  font-size: 24px;
}

/* Class Selector */
.myClass {
  background-color: #fff;
}

/* ID Selector */
#myId {
  border: 1px solid black;
}

```

<hr>

## CSS Function 
  
**CSS functions are built-in functions that allow you to perform calculations, manipulate values, and apply complex effects to your styles. CSS functions take one or more input values and return a modified value that can be used in your styles.**
  
### 1. calc() - performs basic arithmetic operations on values and units.  

```
width: calc(50% - 20px);  
```
### 2. var() - allows you to use variables to define and reuse values.  
  
```
    --primary-color: #007bff;
   color: var(--primary-color);

```
### 3. rgb() / rgba() - defines a color using red, green, blue and optionally an alpha value.

```
     background-color: rgba(255, 0, 0, 0.5);
```

### 4. hsl() / hsla() - defines a color using hue, saturation, lightness and optionally an alpha value.

```
       color: hsl(120, 100%, 50%);
```
  
### 5. url() - defines the location of an external resource such as an image or a font.

```
  background-image: url("background.png");
```
  
### 6. attr() - retrieves the value of an HTML attribute and uses it in the style.

```
  content: attr(title);
```
  
### 7. linear-gradient() / radial-gradient() - creates a gradient background using one or more colors.

```
   background-image: linear-gradient(to right, red, orange, yellow, green);
```
  
### 8. min() / max() - returns the minimum or maximum value from a list of inputs.

```
     width: min(50%, 200px);
```
  
### 9. clamp() - restricts a value between a minimum and maximum value

```
   font-size: clamp(16px, 2.5vw, 24px);
```
  
  
  
  
  
  
  
  

<hr>

- <a href="https://punitkatiyar.github.io/css/start-css.html">css syntax</a>

- css text property
- create article using html css
- text logo using css
- css box layout
- css window 8 start menu
- nested box layout

- > css border

- > css position

- > css navigation

# 🧑🏼‍💻 CSS3 Module For Development <span style='font-size:100px;'></span>

> text-shadow and box-shadow

> border-radius

> border-image

> background-image

> css 2d and 3d

> css animation

> css flex layout

# 🧑🏼‍💻 ref website

>https://coolors.co/palettes/trending

>https://www.w3schools.com/cssref/playit.asp?filename=playcss_filter&preval=none
  
> https://webcode.tools/
  
> https://animista.net/


<hr>
<a href="https://punitkatiyar.github.io/">Back To Home Page</a>
<hr>

<style
  type="text/css">
h1 {color:royalblue;}
p {color:#686e78; font-size:1.2rem;}
</style>
<p>okay</p>

