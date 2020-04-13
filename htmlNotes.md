<style>
p {text-align:justify;}
h1 {color:red;font-weight:bold;}
div {text-align:justify}
mark {background-color: silver;
      color: black;}
li{font-weight: bold;}
</style>

<h1>Basic HTML/HTML5 Notes</h1>
<p> 
These notes mostly follow the <strong><em>Free code camp</em></strong> practisces which I took. There are two type of commands 
<ul>
<li> Self Closing</li> - they dont require a closing tag.
<li> Not Self CLosing</li> - they require a closing tag.
</ul>
<p>I am writing in an ordered list of all the excersices that I have finished. </p>
</p>
<div>
<ol>
<li>Heading Levels</li>
There are six levels of heading. Each can be chosen as per requirement.The heading tags are,

```html
<h1></h1> through <h6></h6>
``` 
Headings are non self closing and require a closing tag.

<li>Paragraph</li>
Paragraphs are marked with 

```html
<p></p>
```
again they are non self closing. 

<li>HTML5 More tags</li>
HTML5 introduces more descriptive HTML tags. These include

```html
<main></main>, <header></header>, <footer></footer>, <nav></nav>, <video></video>, <article></article>, <section></section> 
```
and others.

<li>Adding Images</li>
<p>We can add images to the website using <strong>img</strong> element and point to a specific image's URL using the <strong>src</strong> attribute which is nothing but the source, the source can be any link or may be from your own computer, better to keep inside a project folder as you work. The command looks like below,

```html
<img src="https://www.your-image-source.com/your-image.jpg">
```
Also note that <strong>img</strong> is an self closing element. 
All <strong>img</strong> elements must have an <strong>alt</strong> attribute. The text inside an <mark><strong>alt</strong></mark> attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.</p>

<li>Link to External Pages</li>

<p>Link to external pages can be done with anchor <strong>a</strong>.The <strong>a</strong> elements need a destination web address called an <strong>href</strong> attribute. They also need anchor text. Here's an example:

```html
<a href="https://freecodecamp.org">this links to freecodecamp.org</a>
```
<li>Linking Internal Sections</li>
<p>These can be done using <strong>id</strong> attribute.

```html
<a href="#About me">Click to go to about me</a>
<h2 id="About me">About me</h2>
```
We can see that the <strong>id</strong> attribute is set to <strong>h2</strong> element ad linked to <strong>a</strong> element. Note that anchor elements can aso be nested inside paragraphs </p>


</div>

