**HyperText Markup Language**, is a markup language used to describe the structure of a web page. 
HTML exists to solve the problem of how a rich document can be expressed in plain text

_invented by a physicist, Tim Berners-Lee, to help computers share information_

A markup language is a computer language that defines the structure and presentation of raw text. The computer can interpret raw text that is wrapped in HTML elements

<details>
<summary>Boilerplate</summary>

	<!DOCTYPE html> 
	  <html>
	    <head>
	      <title>My Coding Journey</title> 
	    </head>
	    <body>
	      <p>Hello World</p>
	    </body>
	  </html>

</details>

## Element Structure:

	<p>Hello World</p>

<details>
<summary>Structure Explained</summary>

	  <opening-tag>CONTENT</closing-tag>

"white space collapsing" - no matter how much white space you have in between your code it will not display differently on the actual webpage
</details>

#### Headings 

	<h1>I'm most important! There should really only be one of me</h1>
	<h2>I'm still important! I'm fine being on the page a few times though</h2>
	<h3>I'm pretty common</h3>
	<h4>I'm detailed</h4>
	<h5>I'm probably deep</h5>
	<h6>Wow, that's very detailed</h6>
	
#### Lists 
	<!-- ordered list -->
	<ol>
  	  <li>I'm first</li>
  	  <li>I'm second</li>
  	  <li>I'm third</li>
	</ol>
	<!-- unordered list -->
	<ul>
  	  <li>red</li>
  	  <li>green</li>
  	  <li>blue</li>
	</ul>
	
#### Images 
	<img src="" alt="" />
	<!-- is the same as -->
	<img src="" alt="">
	
**Semantic HTML** 
A semantic element clearly describes its meaning to both the browser and the developer
[Semantic HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
	
	<section>
	<header>
	<footer>
	<nav>
	<main>

## Attribute - extra information about elements :

	<p class="attribute">Hello World</p>

  ex: target=”_blank” 
  Open in New Browser Tab (or Window)

## Hierarchy
Child elements can inherit behavior and styling from their parent element

When an element is contained inside another element, it is considered the child of that element. The child element is said to be nested inside of the parent element

### Additional Resources 

[Lorem Ipsum](https://www.lipsum.com/) - dummy text of the printing and typesetting

```html
<!-- comment -->
```

#### Free image sites
- pixabay
- pexels
- gratisography
- unsplash
