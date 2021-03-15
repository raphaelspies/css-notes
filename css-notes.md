# Linking to a Stylesheet
1. Can be inserted into HTML on the page. 
2. Must be inserted in the <head></head>.
3. Create a link (to another locally saved document) with the following: 
  ```html
  <link href="style.css" type="text/css" rel="stylesheet">
  ```
  
 # Creating Styles
 1. Each style corresponds to an HTML element.
 2. Styles must be written in the following format (using curly braces to delineate each style, and semi-colons to end each line within:
 ```html
p {
  color: green;
  font-weight: bold;
}
```
 4. "Classes" can be referenced as an element using dot notation: `.title`
 5. You can combine different element/class types by separating them with a space in your html, as such:
 ```html
<h1 class="green bold"> ... </h1>
```
6. For element IDs, use the # prefix: `#article-title {...}`
