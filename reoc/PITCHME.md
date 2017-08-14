# Regular Expressions on Command
## Advanced Regexes

---

## Introduction

Regular Expressions are a powerful means of searching and manipulating text-based data, using metacharacters to match the contents of text files, and optionally use the matches to perform replacements.

To recap:

<ul>
<li><pre>\w</pre> matches any alphanumeric character</li><!-- .element: class="fragment" -->
<li><pre>\b</pre> matches the a word boundary position</li><!-- .element: class="fragment" -->
<li><pre>x+</pre> matches one or more instances of <em>x</em></li><!-- .element: class="fragment" -->
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
		<td><pre>find</pre><!-- .element: class="fragment" --></td>
	</tr>
	<tr>
		<td>I want to find <strong>lines</strong> in a file that match a certain pattern</td>
		<td><pre>grep</pre><!-- .element: class="fragment" --></td>
	</tr>
	<tr>
		<td>I want to <em>change</em> <strong>line</strong> in a file according to a pattern</td>
		<td><pre>sed</pre><!-- .element: class="fragment" --></td>
	</tr>
	<tr>
		<td>I have <strong>column-oriented</strong> data and I want to match patterns in one column and update another column</td>
		<td><pre>awk</pre><!-- .element: class="fragment" --></td>
	</tr>
</table>