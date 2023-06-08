# HTML


#HTML
HTML document Strucher


```
<HTMl>
<Header>

   <title>My first HTML Strucher</title>
</Header>

<body>
soruce code
</body>
</HTMl>

```

### HTMl tag's Div and Span

```
<HTMl>
<Header>

   <title>My first HTML Strucher</title>
</Header>

<body>
<Div> Hello this is a div</Div>
<Div> Hello this is a diffrant div or Divrent</Div>

<Span>Hello, who are </Span>
<Span> you ?</Span>
</body>
</HTMl>

```

### HTMl element i,b,p, a
- i is nothing but italic 
- b is nothing but bold
- p element AND This is a block element, so its more like a div and its kind of a replacment of for a div.
- a element is creates a link.

```
<a href="https://github.com/TrickAndTrack"> Git URL</a>
```

### HTML eleemnts  ul, li and ol

- ol <ol> is an acronym for ordered lists.
- ul <ul> is unordered lists.
- li The <li> HTML element is used to represent an item in a list.


```
<div>My Favourite</div>
<ul>
   <li>Food</li>
   <li>Game</li>

</ul>

```
```
<div>My Favourite</div>
<ol>
   <li>Food</li>
   <li>Game</li>

</ol>

```
 
### HTML elements header and footer

- header The <header> element represents a container for introductory content or a set of navigational links.

```
<header hight="100"> My life  </header>

```
- footer The <footer> tag defines a footer for a document or section.

```
<footer>&copy; Copyright2023</footer>
```

### HTML element section, main & article

 - br The <br/> element represent break line

 ```
 <br/>
 ```

 - article The `<article>` tag specifies independent, self-contained content.

 ```
 <article>
   <a href="#"> article 1</a>
   <p>News Realted to article HTML</p>
 </article>

 ```
 - main The <main> HTML element represents the dominant content of the <body> of a document.

 ```
<main>
<article>
   <a href="#"> article 1</a>
   <p>News Realted to article HTML</p>
 </article>
</main>

 ```
 - section The section is another html5 element.

 ```
 <HTMl>
<Header>

   <title>My first HTML Strucher</title>
</Header>

<body>
<section><Div> Hello this is a div</Div>
<Div> Hello this is a diffrant div or Divrent</Div>
 </section>
 <section>Span>Hello, who are </Span></section>
 <section></section>
 <section><Span> you ?</Span></section>
 <section>1</section>
 <section>2   </section>



</body>
</HTMl>

 

 ```

### HTML element - h1,h6 and aside

- H - There is six different levels of H element & H1 is biggest
```
<h1>Headline 1</h1>
<h2>Headline 2</h2>
<h3>Headline 3</h3>
<h4>Headline 4</h4>
<h5>Headline 5</h5>
<h6>Headline 6</h6>
```

- aside  its secondary to main content & The <aside> tag defines some content aside from the content it is placed in.

```
<!DOCTYPE html>
<html>
<head>
<style>
aside {
  width: 30%;
  padding-left: 15px;
  margin-left: 15px;
  float: right;
  font-style: italic;
  background-color: lightgray;
}
</style>
</head>
<body>

<h1>For aside element we need to used css style</h1>

<p>is cover national and international news on economy, politics, defence, sports</p>

<aside>
<p>Today's news: Get latest and Breaking News on Politics, Business, Lifestyle, Entertainment and Sports along with News updates from around the world.</p>
</aside>

<p>is cover national and international news on economy, politics, defence, sports</p>
<p>is cover national and international news on economy, politics, defence, sports</p>

</body>
</html>
```

### HTML element tables

- tables  An HTML table consists of one <table> element and one or more <tr>, <th>, and <td> elements.

- tr The <tr> element defines a table row.
- th The <th> element defines a table header.
- td The <td> element defines a table cell.
- caption The <caption> tag defines a table caption. The <caption> tag must be inserted immediately after the <table> tag.
- The <colgroup> tag specifies a group of one or more columns in a table for formatting. tag is useful for applying styles to entire columns, instead of repeating the styles for each cell, for each row.


- type="text": This is the default type for <input> elements. It displays a single-line text input field.

- type="password": It displays a text input field where the entered text is masked, typically as dots or asterisks, for security reasons.

- type="checkbox": It displays a checkbox that can be selected or deselected by the user.
- type="number": It will  only number in input 
- type="email": 

- type="radio": It displays a radio button that allows the user to select a single option from a group of options.

- type="submit": It displays a button that submits the form data to the server when clicked.

- type="reset": It displays a button that resets the form to its initial values when clicked.

- type="button": It displays a simple button that can be used for custom actions or JavaScript interactions.

- type="file": It displays a file upload control that allows the user to select files from their device.

- type="date", type="time", type="datetime", etc.: These types display controls for entering dates, times, or date-time combinations, depending on the specific type.

```
<style>
table, th, td {
  border: 1px solid black;
}
</style>
<main>
  <table>
  <colgroup>
    <col span="2" style="background-color: lightgrey">
    <col style="background-color: blue">
  </colgroup>
  <caption>Monthly savings</caption>
    <thead>
      <tr>
        <th>Type</th>
        <th>Size</th>
        <th>Atom</th>
      </tr>
    </thead>
         <tr>
            <td>Electronic </td>
             <td> Big Size </td>
              <td>Big screen </td>
         </tr>
    <tbody>

    </tbody>
  </table>
</main>

```

# Advance HTML

### HTML element - img

- img The <img> tag is used to embed an image in an HTML page.
different way of img tag use 
```
<img src="imgone.jpg" />
<img src="C:\Users\TrickAndTrack\imgTwo.png" />
<img width="100%" src="C:\Users\TrickAndTrack\imgTwo.png" />


```

### HTML element - FORM & input

- FORM form is going to be a data set & HTML form is used to collect user 

input.
- An <input> element can be displayed in many ways, depending on the type attribute.

```
<form>
  <label for="fname">Name:</label><br>
  <input type="text" placeholder="Enter your name">

  <label for="password">password</label><br>
  <input type="password" placeholder="Enter your password">

  <input type="checkbox" id="checkbox1" name="checkbox1"><br>
<label for="checkbox1">I agree to the terms and conditions</label>

<input type="radio" id="radio1" name="radioGroup" value="option1"><br>
<label for="radio1">Option 1</label>
<br>
<input type="radio" id="radio2" name="radioGroup" value="option2"><br>
<label for="radio2">Option 2</label>

 <label for="file">fileUpload</label><br>
<input type="file" id="fileUpload" name="fileUpload">

<label for="range">rangeInput</label><br>
<input type="range" id="rangeInput" name="rangeInput" min="0" max="100" value="50">

</form>

```

### HTML element - Select, option & button

- select The <select> element creates a dropdown menu, allowing the user to choose one or more options from a list. 

- Option The <option> element defines an individual option within a <select> element. It is placed inside the <select> tags and represents a selectable item in the dropdown menu.

- Button The <button> element creates a clickable button on a webpage.

```
<select name="size">
<option value="default  ">$0 Doller</option>
<option value="1"> $1 Doller </option>
<option value="2"> $2 Doller </option>
<option value="3"> $3 Doller</option>
<option value="4"> $4 Doller</option>
<option value="5"> $5 Doller</option>
</select>   

```

# html5

### Video tag
> Note: soruce tag has no closing tag.
```
  <video width="540 px" height="320 px"> 
      <soruce src="./video/TrickAndTrack/intro.mp4" type="video/mp4">
  </video>
```
### audio tag

```

<p>Example 1</p>
<audio width="600"  controls>
   <soruce src="./audio/TrickAndTrack/See You Again.mp3" type="audio/mp3">
</audio>

<p>Example 2</p>
<audio width="600"  autoplay>
   <soruce src="./audio/TrickAndTrack/See You Again.mp3" type="audio/mp3">
</audio>

<p>Example 3</p>
<audio width="600"  loop>
   <soruce src="./audio/TrickAndTrack/See You Again.mp3" type="audio/mp3">
</audio>



```

### DOCTYPE

- DOCTYPE tag is going to tell browser what the DOCTYPE is so insance were just gonna write HTML. This is going to tell the browser that this is an html5 document.

```
<!DOCTYPE html>

``` 

### meta tag

- META tags basically provide more informtion to browser about our webpage and much like the entire header really but the meta tags provide meta data.
- Character encoding: Character encoding refers to the way characters are represented and stored in a computer's memory.
- <meta> tag: The <meta> tag is an HTML tag used to provide metadata about the HTML document. It is placed in the <head> section of the HTML document, and its purpose is to convey information about the document to the browser or search engines.
- charset attribute: The charset attribute is used within the <meta> tag to specify the character encoding of the HTML document. 

- UTF-8 (Unicode Transformation Format 8-bit) is a widely used character encoding that can represent almost all characters from various writing systems in the world. It is backward compatible with ASCII (American Standard Code for Information Interchange), which means that the first 128 ASCII characters are represented the same way in UTF-8.

```
<!DOCTYPE html>
   <head>
   <title>Best News Tv Channel</title>
   <meta charset="UTF-8">
   </head>
```

## Question

#### Question 1 What is a div element is ?

Answer 
- it's callled a Block element.
#### Question 2 What is a span element is ?

Answer 
- The opposite a block element is a inline element and it is not full width. it is only as tall and as wide as it has to be that is callled a span element.
- it is only one line element and that because this is one span element.
