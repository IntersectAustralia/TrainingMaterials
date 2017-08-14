# Regular Expressions on Command
## Advanced Regexes

---

## Introduction

Regular Expressions are a powerful means of searching and manipulating text-based data, using metacharacters to match the contents of text files, and optionally use the matches to perform replacements.

<ul>
<li>\w matches any alphanumeric character</li><!-- .element: class="fragment" -->
<li>\b matches the a word boundary position</li><!-- .element: class="fragment" -->
<li>x+ matches one or more instances of <em>x</em></li><!-- .element: class="fragment" -->
</ul>

<p>For full details, find and download a Regex cheat sheet!</p><!-- .element: class="fragment" -->

+++

## Introduction

This course will show you how to combine your knowledge of regular expressions with four powerful command line utilities that have regex support

Here are some common tasks you might want to perform…

+++

## Introduction

<table>
	<tr>
		<td>I want to find <strong>files</strong> or <strong>directories</strong> that match a certain pattern</td>
		<td><span style="font-family: Courier, monospace; background-color: red; color: white">find</span><!-- .element: class="fragment" --></td>
	</tr>
	<tr>
		<td>I want to find <strong>lines</strong> in a file that match a certain pattern</td>
		<td><span style="font-family: Courier, monospace; background-color: orange">grep</span><!-- .element: class="fragment" --></td>
	</tr>
</table>

+++

## Introduction

<table>
	<tr>
		<td>I want to <em>change</em> <strong>line</strong> in a file according to a pattern</td>
		<td><span style="font-family: Courier, monospace; background-color: purple; color: white">sed</span><!-- .element: class="fragment" --></td>
	</tr>
	<tr>
		<td>I have <strong>column-oriented</strong> data and I want to match patterns in one column and update another column</td>
		<td><span style="font-family: Courier, monospace; background-color: green"><pre>awk</pre></span><!-- .element: class="fragment" --></td>
	</tr>
</table>