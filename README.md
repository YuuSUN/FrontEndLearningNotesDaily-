# FrontEndLearningNotesDaily
## Menu 

Week | Mon | Tue | Wed | Thu | Fri | Sat | Sun  
:-: | :-: | :-: | :-: | :-: | :-: | :-: | :-:
March 16-22  | | | [1](https://github.com/YuuSUN/FrontEndLearningNotesDaily#20200318day-one-html-basics)| [2](https://github.com/YuuSUN/FrontEndLearningNotesDaily#20200319day-two-html-semantic-elements) ||||

- [Day One: HTML Basics](https://github.com/YuuSUN/FrontEndLearningNotesDaily#20200318day-one-html-basics)
- [Day Two: HTML Semantic Elements](https://github.com/YuuSUN/FrontEndLearningNotesDaily#20200319day-two-html-semantic-elements)


### 【2020/03/18】Day One: HTML Basics
#### 1. What is HTML  

- Hypertext Markup Language. e.g. If you want to publish the content of rich-text on the forum, you need some codes additionally. 

```html
[del]Arschloch[/del]
``` 
- The example indicates the text between labels should be deleted. Strikethrough effect will be added by default. 
- HTML and CSS(Cascading Style Sheet 层叠样式表)are two of the core technologies for building web pages. HTML builds the structure of page, CSS the layout. 
- retrieve online information via hypertext links, at the click of a button.
- With HTML, authors describe the structure of pages using markup. The elements of the language label pieces of content such as “paragraph,” “list,” “table,” and so on.

#### 2. What is XHTML
- XHTML is the variant of HTML that using the syntax of XML, the extensible markup language. XHTML has all the same elements as the HTML variant, but the syntax is slightly different. Because XHTML is a XML application, you can use other XML tools with it.

#### 3. What is CSS
- CSS is the language for describing the presentation of web pages, including colors, layout and fonts. It allows one to adapt the presentation to different types of devices. CSS is independent of HTML and can be used with any XML-based markup language. The separation of HTML from CSS makes it easier to maintain sites, share style sheets across pages, and tailor pages to different environments.

#### 4. What is Javascript 
- Tools for adding dynamic effects to web pages
- e.g. Creat a ```<div>```（块级元素）window when mouse hovering over the label.

#### 5. Examples
The following very simple example of a portion of an HTML document illustrates how to create a link within a paragraph. When rendered on the screen (or by a speech synthesizer), the link text will be “final report”; when somebody activates the link, the browser will retrieve the resource identified by “http://www.example.com/report”:
```
<p class="moreinfo">For more information see the
<a href="http://www.example.com/report">final report</a>.</p>
``` 
The class attribute on the paragraph's start tag (“```<p>```”) can be used, among other thing, to add style. For instance, to italicize the text of all paragraphs with a class of “moreinfo,” one could write, in CSS:    

``` 
  p.moreinfo { font-style: italic }
``` 
By placing that rule in a separate file, the style may be shared by any number of HTML documents.

#### 6. More Information
For more information about HTML and CSS, see [tutorials for HTML and CSS](https://www.w3.org/2002/03/tutorials.html#webdesign_htmlcss).  

For advanced document transformations and layout beyond CSS, see [XSLT](https://www.w3.org/standards/xml/transformation) & [XSL-FO](https://www.w3.org/standards/xml/publishing).



 

 
### 【2020/03/19】Day Two: HTML Semantic Elements 
#### 1. What are semantic elements
- Semantic elements = elements with a meaning 
- Semantic elements describes its meaning to both the browser and the developer.
- Examples of **none-semantic** elements: ``` <div>``` and ``` <span>``` - Tells nothing about its content.
- Examples of **semantic** elements: ``` <form>``` ,``` <table>``` and ``` <article>``` - Clearly defines its content.

#### What is HTML5
- HTML 5 is the newest standard of html, it has more abundant semantics, graphics and multimedia contents. 

#### What is doctype 
- ```<!DOCTYPE>``` declaration help the browser show the web correctly. 
- HTML has many different versions. Only when the browser understand the exact version of html can it show the content correctly.

#### HTML Emelments 
- An HTML element usually consists of **start** tag and an **end** tag. ```<tagname>content goes here</tagname>```
- The html element is everything from the start tag to the end tag. 
- HTML elements with no content are called empty elements. Empty elements do not have an end tag such as the ```<br>```element (which indicates a line break)
- HTML elements can be nested (elements can contain elements).
- The ```<html>``` element defines the whole document. Inside the <html> element is the <body> document. 
- HTML5 does not require empty elements to be closed. But if you want stricter validation, or if you need to make your document readable by XML parsers, you must close all HTML elements properly.
- HTML is Not Case Sensitive: ```<P>``` means the same as ```<html>```. 

####
  
