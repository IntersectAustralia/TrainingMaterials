# Regular Expressions on Command
## <em>Advanced Regexes</em>

---?include=assets/training_introduction.md

---
## Introduction

Regular Expressions are a powerful means of searching and manipulating text-based data, using metacharacters to match the contents of text files, and optionally use those matches to perform replacements.

<ul>
<li>\w matches any alphanumeric character</li><!-- .element: class="fragment" -->
<li>\b matches the a word boundary position</li><!-- .element: class="fragment" -->
<li>x+ matches one or more instances of <em>x</em></li><!-- .element: class="fragment" -->
</ul>

For full details, find and download a Regex cheat sheet!<!-- .element: class="fragment" -->

+++

### Introduction

This course will show you how to combine your knowledge of regular expressions with four powerful command line utilities that support regular expressions.

Here are some common tasks you might want to perform…

+++

### Introduction

<table>
	<tr>
		<td>I want to find <strong>files</strong> or <strong>directories</strong> that match a certain pattern</td>
		<td><span style="font-family: Courier, monospace; background-color: red; color: white">find</span><!-- .element: class="fragment" --></td>
	</tr>
	<tr>
		<td>I want to find <strong>lines</strong> in a file that match a certain pattern</td>
		<td><span style="font-family: Courier, monospace; background-color: orange; color: black">grep</span><!-- .element: class="fragment" --></td>
	</tr>
</table>

+++

### Introduction

<table>
	<tr>
		<td>I want to <em>change</em> <strong>line</strong> in a file according to a pattern</td>
		<td><span style="font-family: Courier, monospace; background-color: purple; color: white">sed</span><!-- .element: class="fragment" --></td>
	</tr>
	<tr>
		<td>I have <strong>column-oriented</strong> data and I want to match patterns in one column and update another column</td>
		<td><span style="font-family: Courier, monospace; background-color: green; color: black">awk</span><!-- .element: class="fragment" --></td>
	</tr>
</table>

---

### Some key points

In this selection of 4 commands, <span style="font-family: Courier, monospace; background-color: red; color: white">find</span> is differentiated by the fact that it is used to find <b>file names</b> or <b>directory names</b> that match a certain criteria. It does not operate on the contents of files. 

All the rest work with the <b>contents of files</b>.

If your needs exceed the capabilities of these tools, you probably need to use a programming language (Python, Ruby, Perl, etc.)

---
# <span style="font-family: Courier, monospace; background-color: red; color: white">find</span>

+++

## <span style="font-family: Courier, monospace; background-color: red; color: white">find</span>

`find` is a powerful tool for finding files and directories.
Once found, matching files can be:

- printed out to the screen (kind of like `ls`)
- passed to another program for further processing
- deleted (dangerous!)

+++

## <span style="font-family: Courier, monospace; background-color: red; color: white">find</span> vs <span style="font-family: Courier, monospace">ls</span>

- `find` is in many ways more complex and more powerful than `ls`.
- `find` will by default search all directories below the specified directory (it is recursive). 
- `ls` will only list the specified directory by default.
- `find` is convenient for building a workflow, by allowing you to run a command for each found file.
 
+++ 

### Example 1
#### Discover a directory structure

`find data/`

- List all files and directories within the `data/` directory.

- Great for discovering or rediscovering the structure of a directory. But the list can get long…

+++

### Criteria

`find` allows us to set criteria based on most characteristics of files:

<ul style="font-size: 0.6em;">
<li><strong>Type</strong> (e.g. file or directory)</li>
<li><strong>Name</strong> (what is it called)</li>
<li><strong>Path</strong> (where is it located)</li>
<li>Time stamps  (creation, last modification, last access)</li>
<li>Size (empty or some number of bytes)</li>
<li>Ownership (which user owns it and to which group does it belong?)</li>
<li>Depth (how many directories deep is it)</li>
<ul>

Let's look at the <strong>important</strong> ones.

+++

### Example 2
#### Show only directories

`find data/ -type d`

- List all directories contained within the `data/` directory.

- Much better for determining how the data is organised.

+++

### Example 3
#### Show only files

`find data/ -type f`

- List all files contained within the `data/` directory. 
- Directories are now excluded from the list.

- But how many files do we have?

`find data/ -type f | wc -l`

<em>That's a lower-case L, not the number 1!</em>

---?include=assets/closing.md