# HTML

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
## Question

#### Question 1 What is a div element is ?

Answer 
- it's callled a Block element.
#### Question 2 What is a span element is ?

Answer 
- The opposite a block element is a inline element and it is not full width. it is only as tall and as wide as it has to be that is callled a span element.
- it is only one line element and that because this is one span element.

