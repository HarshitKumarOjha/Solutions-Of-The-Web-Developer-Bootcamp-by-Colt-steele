### `<!doctype html>` : 

is to indicate that your html file is using html 5

### `<html>` : 
html is the root element

### `<head>` : 

provides general information (metadata) about the document , title , links ,style sheets , font files.
         (basically what we don't see)

### `<body>` : 
represents the content of an html document.            

### `comments` : 

`<!--    -->`

### `tags` :

`<h1> <p> <ul>`

- block level : which take up their own line
- inline : work inside a line

- `<title>` : the search engines shows the name of the webpage as the title. 

- `<h1>` : the most important heading and `<h6>` is least. (these are block lvl elements)

- `<p>` : represents paragraph of text. Paragraphs are block laevel elements.

- `<b>` : bold tag (inline element) but this is not the best way in html5 to bold 
      so we have to use `<strong>` which is much more meaning full.

- `<i>` : italicise the text but we will use `<em>` which is basically same but better.

- `<b>` & `<i>` : are about the style ... but `<strong>` & `<em>` are more about the look.

### lists : 
ordered (numbers) and unordered (bullet points) lists...lists can be nested.
```html
<ol>
    <li> List Items </li>
</ol>
<ul>
    <li> List Items </li>
</ul>
```
### `<div>` : 

a div is a generic container...basically a way to group things together. (block level element)

### `<span>` : 
an inline container for grouping/selecting things together.

### Attributes : 

additional information to tags 
```html
<tag name="value"></tag>
<img src="corgi.png">
<p class="selected"> woof woof </p>
<a href="www.google.com"> click me to go to google </a>    (inline element)
<link rel="stylesheet" type="text/css" href="style.css">
```
### Tables :
```html
<table>
    <thead>
        <tr>
            <th> Table Header 1 </th>
            <th> Table Header 2 </th>
        </tr>
    </thead>
    <tbody>    
        <tr>
            <td> Table Data 1 </td>
            <td> Table Data 2 </td>
        </tr>
    </tbody>    
</table>
```
### `<input>`: 
there are tonnes of input tags.
```html
<input type = "text">
<input type = "password">
<input type = "radio">
<input type = "color">
<input type = "submit">
```
### Forms: 

putting input tags inside the Form tags makes a form. form is a block lvl element.

**some additional arguments :**
    `placeholder = "username here"`
    `placeholder = "password here"`

**example:**
```html
<form action="https://www.wikipedia.org" method="get">
	<input type="text" name="username" placeholder="username">
	<input type="password" name="password" placeholder="password">
	<input type="submit">
</form>
    <!-- action- where the form send data to -->
    <!-- method- what HTTP method (get/post) -->
```
### lables: 

we use lables for people who are blind and use screen reader.

### validations: 
- "required" is the attribute for the form validation. through which a form can't be left empty
- by selecting the type="Email" and attribute reqiured , it shows the validation of "@"" sign

**example:**
```html
<form action="http://www.wikipedia.org" method="get">
	<label for="Username">Email:</label>
	<input id="Username" type="Email"  name="Username" placeholder="Email" required>

    <label for="password">Password:</label>
    <input id="password" type="password" name="password" placeholder="password" required>

	<input type="submit">
</form>
```



