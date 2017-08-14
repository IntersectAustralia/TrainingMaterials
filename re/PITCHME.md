## Powerful text searching and matching with Regular Expressions

---

### General Introduction

- Intersect (http://intersect.org.au)
   - Who are we?
   - Your trainers
- Your University IT Contacts
- General Housekeeping
   - Toilets
   - Coffee and water facilities
   - Emergency exits

---

![Logo](https://imgs.xkcd.com/comics/regular_expressions.png)

https://xkcd.com/208/

---

### Find and Replace

<ul>
<li>Most people will be aware of the <strong>find</strong> and <strong>replace</strong> options of programs such as <em>Word</em>.</li>
<li>Often we use find to <strong>locate</strong> the occurrence of a particular word, phrase or number.</li>
<ul>
<li><em>realize</em></li><!-- .element: class=<em>fragment</em> -->
<li><em>cookie</em></li><!-- .element: class=<em>fragment</em> -->
<li><em>3.1415927</em></li><!-- .element: class=<em>fragment</em> -->
</ul>
</ul>
+++

#### Sometimes the objective is…
<ul>
<li>to find out how many matches there are</li>
    <ul><li>101 occurrences of <em>realize</em></li></ul><!-- .element: class=<em>fragment</em> -->
<li>to locate each match and review it in context</li> 
    <ul><li><em>cookie</em> occurs before <em>monster</em></li></ul><!-- .element: class=<em>fragment</em> -->
<li>to replace or substitute that match for something else</li>
    <ul><li><em>replace 3.1415927 with π</em></li></ul><!-- .element: class=<em>fragment</em> -->
</ul>

---

### Regular Expressions

can be used to make *more sophisticated* matches and *more complex* substitutions.

+++

#### You might want to find…
<ul>
<li>all the phone numbers or email addresses in a document</li><!-- .element: class=<em>fragment</em> -->
<li>all the hashtags in a collection of tweets</li><!-- .element: class=<em>fragment</em> -->
<li>all the words that start with <em>e</em> and end in <em>ed</em>, irrespective of length</li><!-- .element: class=<em>fragment</em> -->
<li>all words at the end of a line of text</li><!-- .element: class=<em>fragment</em> -->
<li><em>honest</em> words, like <em>honor</em>, <em>honour</em>, <em>honorable</em>, <em>honesty</em>, etc.</li><!-- .element: class=<em>fragment</em> -->
</ul>
+++

#### Conceptual leap

Note the leap from looking for a literal match (<em>#auspol</em>) to matching a pattern

All things that look like a hashtag; a # character followed by alphanumeric characters



---

### Regexes are… 

+++
#### …Everywhere!
<ul>
<li>Most good text editors, TextWrangler, Notepad++, Jedit, Vim…</li><!-- .element: class="fragment" -->
<li>Google Spreadsheets</li><!-- .element: class="fragment" -->
<li>Microsoft Word (a reduced set anyway)</li><!-- .element: class="fragment" -->
<li>Open Refine</li><!-- .element: class="fragment" -->
<li>Command Line programs, sed, grep…</li><!-- .element: class="fragment" -->
<li>Programming languages, Perl, Python, Ruby, R…</li><!-- .element: class="fragment" -->
<li>Online sandpits</li><!-- .element: class="fragment" -->
</ul>
+++

#### …Very old
<ul>
<li>Developed in 1950s</li><!-- .element: class="fragment" -->
<li>Based on characters in basic set </li><!-- .element: class="fragment" -->
<li>Many extensions since then</li><!-- .element: class="fragment" -->
<li>Some variation in syntax between implementations</li><!-- .element: class="fragment" -->
</ul>
+++

#### …Frustrating
<ul>
<li>Syntax is easily forgotten</li><!-- .element: class="fragment" -->
<li>Some matches might not be possible</li><!-- .element: class="fragment" -->
</ul>
+++

#### …Not machine learning

<ul>
<li>Regular expressions are not an example of machine learning</li><!-- .element: class="fragment" -->
<li>You need to specify the pattern – the rule – that matches what you want, and <em>only</em> what you want</li><!-- .element: class=<em>fragment</em> -->
<li>This is sometimes challenging, and occasionally impossible</li><!-- .element: class=<em>fragment</em> -->
</ul>

+++

#### …Powerful!

- Once you learn them, you will see applications everywhere

---

### So!

Let's get started!

+++

#### Exercise 1: Avian Internet

- RegExr
   - http://www.regexr.com
- RFC2549
   - http://bit.ly/1MLmg7C

+++

#### Exercise 2: To die upon a kiss

- RegExr
   - http://www.regexr.com
- Full text of Othello
   - http://bit.ly/1tKfAMW

+++

#### Exercise 3: Substituting names

- RegExr
   - http://www.regexr.com
- Random name generator
   - http://bit.ly/1MLmknO

+++

#### Exercise 5: Reformatting dates

- RegExr
   - http://www.regexr.com
- Dates in American History
   - https://goo.gl/35lQXi

---

## Summing up

+++

### We have seen that…
<ul>
<li>Regular expressions are a powerful means of matching patterns in text data</li><!-- .element: class="fragment" -->
<li>Regular expressions allow you to perform complex pattern substitutions</li><!-- .element: class="fragment" -->
<li>This is very useful for analysing and modifying unstructured text</li><!-- .element: class="fragment" -->
<li>This is also useful in working with structured text: html, xml, csv…</li><!-- .element: class="fragment" -->
</ul>

+++

### Next steps
<ul>
<li>Find out how to use regular expressions with your data</li><!-- .element: class="fragment" -->
<li>Look out for regular expression options in your text editor's search and replace function</li><!-- .element: class="fragment" -->
<li>Search the internet for <em>regular expressions cheat sheet</em> and grab a copy of one that you like</li><!-- .element: class="fragment" -->
</ul>
---

### Thank you for attending!

- Please complete our course survey: [svy.mk/18c8dHa](http://svy.mk/18c8dHa)
- Get in contact with us if you have questions: [training@intersect.org.au](mailto:training@intersect.org.au)
- Join Intersect's Training mailing list for info on upcoming courses:
   - Send an email to [learn+subscribe@intersect.org.au](mailto:learn+subscribe@intersect.org.au)
