# LJ Code 301 - Day 5

On Day 5, I learned about marked.js and highlight.js. 

Marked is a javascript library which parses and compiles markdown into html. It also allows you to set a function to highlight the code (and there are multiple prebuilt options provided by libraries such as pygmintize and highlight.js. It also enables you to override how tokens are rendered to html, set whether or not it should be GitHub-flavored markdown (including tables and line breaks), conform to obscure parts of markdown.pl (the orginal markdown perl script), ignore input HTML, change list behavior and use smart typographic punctuation for things like quotes and dashes. You can also directly access the lexer to manipulate the tokens.

Highlight.js is a code highlighter for many different programming languages. If you put the code inside 
```html
<pre><code>...</code></pre>
```
and then call 
```js
hljs.initHighlightingOnLoad();
```
then it will find the code, detect the language, and highlight it automatically. You can specify the language with a class, such as 
```html
<code class="html">...</code>
```
You can also highlight manually with:
```js
hljs.highlightBlock(block);
```